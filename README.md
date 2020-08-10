# udm_urdf
Travaux pratiques concernant l'utlisation de l'urdf

Ces fichiers continnent des différents urdf crée pour les travaux pratiques pour le cours : Robotique industrielle. Pour pouvoir utiliser ce package il faut installer le package joint_state_publisher_gui, en faisant;

sudo apt install ros-<your_ros_version>-joint-state-publisher-gui.

Et si besoin est de faire chmod +X du directoire.

Pour lancer un fichier urdf il faut passer la commande suivante;
roslaunch udm_urdf visualize_urdf.launch model:='$(find udm_urdf)/urdf/main.urdf'

Et sur rviz cliquer sur ADD, puis Robot Model

Et donc pour visualiser les différents fichiers urdf qui sont; box.urdf, mesh.urdf, cylinder.urdf, sphere.urdf, et main.urdf, il suffit de changer le dernier argumen dans roslaunch
