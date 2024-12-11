# rugged_environments
A repository to house challenging simulation environments.

## Pybullet

This is currently the only provided example.

```
git clone --recurse-submodules https://github.com/RPL-CS-UCL/rugged_environments
python3 -m venv my_venv
source my_venv/bin/activate
pip install pybullet
python3 rugged_environments/pybullet/load_env.py
```

Or, from code to create the urdf file and resolve paths for meshes:
```
from rugged_environments.common import make_copy_urdf, FLAT_FLOOR_NAME

urdf_file_and_path = make_copy_urdf(FLAT_FLOOR_NAME)
```

## Isaac Sim

## Mujoco

## Gazebo