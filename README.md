# RPA0001_GraphInteractionUsers

## Live Demo: https://www.youtube.com/watch?v=45cBP2Qi0CE
RPA0001_GraphInteractionUsers is a UiPath Robot. The composition of the architecture uses the REF Framework of UiPath, in the dispatcher state an http request to the graph is made and all the users of the Azure tenant are populated to the orchestrator. After that in the process state another http get all the data for each user and save the information in an excel. 
