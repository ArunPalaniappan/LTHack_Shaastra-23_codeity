# L&amp;T Hackathon Shaastra'23

**Team Name**: `codeity` <br>
**Team Members**: Arun Palaniappan <br>

## Approach

The Problem Statement requires us to use Transfer learning based CNN architechture for classifying ships into categories.

### Model

I have taken a pre-trained **DenseNet-201** model, unfroze the last couple of layers to train on our dataset.

## Results

| Metrics | Test Split |
| :----- | :-----: |
| Kappa score |**0.9346** |
