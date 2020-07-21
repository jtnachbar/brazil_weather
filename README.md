# Brazil Weather Prediction
### By Jamie Nachbar
This is a project seeking to predict weather in the Brazilian city of Rio de Janeiro using a neural network in PyTorch.
<div style="text-align:center"><img src="https://blog.rentcars.com/wp-content/uploads/2019/10/things-to-do-rio-de-janeiro-1.jpg"></a></div>

### Data
This project uses ten years of weather data from one of the weather stations in Rio de Janeiro. As input, the model takes the past eight hours of data consisting of eight weather features per hour. The model performs a regression, aiming to calculate the total rainfall in the next four hours.

### Architecture
The network is a standard feedforward network with 64 input neurons, two hidden layers, and 1 output neuron, containing the predicted rainfall. The network and data is loaded onto a GPU for faster computation.
