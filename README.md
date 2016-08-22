# Azure-Linux-DSVM-plus-extras
Automatically deploys in Azure the Linux DSVM using a template + installs the latest Keras, Theano and  XGBoost

echo "Upgrading XGBoost to the latest version..."
pip install -U xgboost
pip3 install -U xgboost

echo "Installing Keras..."
pip install -U keras
pip3 install -U keras
