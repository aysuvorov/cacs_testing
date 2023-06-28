# CACS testing repository from A.Yu.Suvorov


Использование графовых методов по задачам классификации.

[Обзорная статья](https://aysuvorov.github.io/docs/pages/networks/paren_syn_corr_guide/) А.Ю.Суворова в качестве вводной теоретической базы.

---

Using graph-based methods for classification tasks.

[An overview article](https://aysuvorov.github.io/docs/pages/networks/paren_syn_corr_guide/) by A.Yu. Suvorov serves as an introductory theoretical basis.


## Convolutional NN's with graph classification ([Convo-network-with-graphs](https://github.com/aysuvorov/cacs_testing/tree/main/Convo-network-with-graphs))

Репозиторий содержит информацию о методах представления данных в виде графов с последующей отправкой графа в сверточную нейросеть. 

В основе лежат модули Python - sklearn, networkX, PyTorch.
Прикладная реализация возможна на R.

Фактически, оптимизации требует преобразование показателей индивидуальной биологической системы в граф. 

Требует сторонней загрузки модулей из [Python_scripts](https://github.com/aysuvorov/medstats/tree/master/Python_scripts)

---

This repository contains information about methods for representing data as graphs, with subsequent sending of the graph to a convolutional neural network.

The underlying Python modules include sklearn, networkX, and PyTorch. The practical implementation is possible in R.

In fact, the optimization requires the transformation of the indicators of an individual biological system into a graph.

It requires the installation of third-party modules from [Python_scripts](https://github.com/aysuvorov/medstats/tree/master/Python_scripts).

## Time series approaches for assessing biologic system dynamic changes ([Ts-graph-methods](https://github.com/aysuvorov/cacs_testing/tree/main/Ts-graph-methods))

Демонстрация методов обработки временных рядов с помощью графов. Использован паренклитический подход M.Zanin и корреляционные графы А.Горбаня. 

Необходимые скрипты находятся в папке. 

Также требует сторонней загрузки модулей из [Python_scripts](https://github.com/aysuvorov/medstats/tree/master/Python_scripts)

---

Demonstration of time series processing methods using graphs. M. Zanin's parankleitic approach and A. Gorban`s correlation graphs are used.

The necessary scripts are located in the folder.

It also requires the installation of third-party modules from [Python_scripts](https://github.com/aysuvorov/medstats/tree/master/Python_scripts).

