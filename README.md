# To run the code
We use the FederatedScope framework

TODO: python federatedscope/main.py --cfg federatedscope/gfl/baseline/isolated_gin_minibatch_on_cikmcup.yaml --client_cfg federatedscope/gfl/baseline/isolated_gin_minibatch_on_cikmcup_per_client.yaml

# Brief introduction of the developed algorithm
Our code is modified on the "isolated training" baseline, we increased the hidden of the model to 1028 and modified the learning rate of some clients to prevent the gradient from exploding，and then increased the number of training rounds to 40 rounds.



