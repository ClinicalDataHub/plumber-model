Cars Model Application (API)
================

The code here creates a [Shiny](https://shiny.rstudio.com) application
that interacts with the cars model API defined in
[model-api](../model-api). A deployed version of the application can be
accessed [here](https://colorado.rstudio.com/rsc/car-model-app/).

The [`config`](https://github.com/rstudio/config) package is used to
identify where the API is hosted (either localhost or on [RStudio
Connect](https://www.rstudio.com/products/connect/)). When run locally,
this application uses the default configuration, which expects the
Plumber API to be running locally on `localhost:5762`. When this
application is deployed to RStudio Connect, it looks for the API hosted
at
<https://colorado.rstudio.com/rsc/carmodel>.

[![](images/app-demo.gif)](http://colorado.rstudio.com/rsc/car-model-app/)
