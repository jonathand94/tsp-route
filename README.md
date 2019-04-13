# TSP-Travel-Route

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

Solving the Traveling Salesman Problem using google OR-Tools.

## Features

* Spend less time to visit more places of interest.

* Four modes to choose including walking, driving, bicycling and transit.

* Good visualization powered by gmaps, provide two different kinds of maps.

![route showed on the map](googlemap.JPG)

## Introduction of Travelling salesman problem

"The **travelling salesman problem** (**TSP**) asks the following question: "Given a list of cities and the distances between each pair of cities, what is the shortest possible route that visits each city and returns to the origin city?" It is an [NP-hard](https://en.wikipedia.org/wiki/NP-hardness)problem in [combinatorial optimization](https://en.wikipedia.org/wiki/Combinatorial_optimization)." (**more details on** [**Wikipedia**](https://en.wikipedia.org/wiki/Travelling_salesman_problem))

## usage

* Make sure you have already installed these packages: googleplaces, googlemaps, gmaps, ortools.

* Get Google API key from here: [https://developers.google.com/maps/documentation/distance-matrix/start#get-a-key](https://developers.google.com/maps/documentation/distance-matrix/start#get-a-key).

* Change the variables 'places' and 'location' then run all the cells.

* PS: If the fig is not showed after running all cells, try to restart the Jupyter notebook.

## Environment

<details>
<summary>python-google-places 1.4.1</summary>

```
pip install python-google-places
```

</details>

<details>
<summary>googlemaps 3.0.2</summary>

```powershell
pip install googlemaps
```

</details>

<details>
<summary>gmaps 0.8.4</summary>

```powershell
pip install gmaps
```

</details>

<details>
<summary>OR-Tools v7.0 (2019-03)</summary>

```powershell
python -m pip install --upgrade --user
```

</details>

## Chinese

* [中文教程](https://luochang.ink/2019/04/09/%E7%94%A8Jupyter-notebook%E8%A7%84%E5%88%92%E6%97%85%E8%A1%8C%E8%B7%AF%E7%BA%BF/)

## License
MIT License
