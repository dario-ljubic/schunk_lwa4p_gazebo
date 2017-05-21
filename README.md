# schunk_lwa4p_gazebo
Schunk LWA4P Gazebo model


# Adding custom models
To be able to load models from schunk_lwa4p_gazebo, modifications in .bashrc are needed. Add the following line.
* `export GAZEBO_MODEL_PATH=$(rospack find schunk_lwa4p_gazebo)/models:${GAZEBO_MODEL_PATH}`
