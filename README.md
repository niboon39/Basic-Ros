# Basic-Ros

* Step 1 : Prepare workspace
   -$ mkdir "workspace"
      -$ cd "workspace"
      -$ mkdir src
         -$ cd src
         -$ mkdir "Project folder"
            -$ cd "Project folder"
               -$ mkdir urdf
               -$ mkdir launch
               -$ mkdir model
                  -$ cd model 
                  -$ mkdir meshes
               -$ mkdir src
         
         
* Step 2 : Robot model 

![223172638_148948163982321_5904538159788275801_n](https://user-images.githubusercontent.com/30637687/127641904-359c5bb2-f322-48a2-8754-0416e0a09960.jpg)


* Step 3 : urdf/XML/link
   - http://wiki.ros.org/urdf/XML/link
 
    *format 
           <link name="my_link">
            <inertial>
              <origin xyz="0 0 0.5" rpy="0 0 0"/>
              <mass value="1"/>
              <inertia ixx="100"  ixy="0"  ixz="0" iyy="100" iyz="0" izz="100" />
            </inertial>
            <visual>
              <origin xyz="0 0 0" rpy="0 0 0" />
              <geometry>
                <box size="1 1 1" />
              </geometry>
              <material name="Cyan">
                <color rgba="0 1.0 1.0 1.0"/>
              </material>
            </visual>
            <collision>
              <origin xyz="0 0 0" rpy="0 0 0"/>
              <geometry>
                <cylinder radius="1" length="0.5"/>
              </geometry>
            </collision>
          </link>
          
* Step 4 : urdf/XML/joint
   - http://wiki.ros.org/urdf/XML/joint
   
      *format
         
         
 
