# Skanestas test

Skanestas test to vacancy Quantitative Analyst / Data scientist

Solution based on VGA, used in [Detecting time lag between a pair of time series using visibility graph algorithm](https://www.researchgate.net/publication/349656577_Detecting_time_lag_between_a_pair_of_time_series_using_visibility_graph_algorithm)

Normalised prices from selected small range
![alt text](https://github.com/asferatum/skanestas/blob/main/prices_norm.png?raw=true)

Output Frobenius Norm for each to each graphs in range (start, stop, step)
![alt text](https://github.com/asferatum/skanestas/blob/main/output.png?raw=true)

Full search parameters be like here:
```rb
lag_searchs = [{'name':'0-1', 'first':fts_names[0], 'second':fts_names[1], 'dir': -1, 
                'window_len':150000, 'start':0.0, 'stop':1.0, 'step':5000, 
                'lag_limit_devider': 1.0, 'lag_step_devider': 50, 'array_fullnes':50,
                'status':True}]
```
