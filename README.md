# service_use_timelines

Two versions of the code exist in this repository. A jupyter notebook (service\_use\_timelines.ipynb) and a python file (service\_use\_timeines.py).
Both require a single input file, provided in data\mock_carenotes.csv
This dataset contains anonymised client service use data.

Using the matplotlib library, the code will create a Service Use Timeline for each individual client based on their service use as recorded in the dataset. Each individual matplotlib graphic is saved in a svg format.

For each Service Use Timelime, the x axis is the full 3 year timeline & the y axis is the individual services accessed, with the option to rank the services chronologically or by cost. The duration of the service use is represented by a horizontal bar. The setting and locality of each service is shown by a colour code, and the individual contacts the client had with the service are represented by dots within the service use bar.
