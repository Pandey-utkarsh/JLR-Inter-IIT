# JLR-Inter-IIT
This repository contains the gist of my contribution to the JLR PS in Inter-IIT Tech Meet 11.0 | IIT Kanpur

Created a Novel Data Set of Side view of cars, with open charging points.


![Screenshot from 2023-07-11 02-09-36](https://github.com/Pandey-utkarsh/JLR-Inter-IIT/assets/91661580/9a20da86-f639-4a91-b7e9-f328faa7ca92)
![Screenshot from 2023-07-11 02-09-13](https://github.com/Pandey-utkarsh/JLR-Inter-IIT/assets/91661580/a31007dd-b809-4cdd-8ba4-6f1a3582ae02)


![Screenshot from 2023-07-11 02-03-03](https://github.com/Pandey-utkarsh/JLR-Inter-IIT/assets/91661580/c9f2595d-ccd0-49e6-9343-56da143a19e3)

Annotated Dataset was trained on Yolo-V7. Following are the results:


![Screenshot from 2023-07-11 02-03-42](https://github.com/Pandey-utkarsh/JLR-Inter-IIT/assets/91661580/c0ee3d64-3fba-4cde-94dd-659d0eed0339)

![Screenshot from 2023-07-11 02-03-29](https://github.com/Pandey-utkarsh/JLR-Inter-IIT/assets/91661580/4fd3d7d8-0b08-44a4-b507-1e44e8e2418c)

![Screenshot from 2023-07-11 02-03-53](https://github.com/Pandey-utkarsh/JLR-Inter-IIT/assets/91661580/2f481c2f-e9b1-434e-87b5-65e72bc0c23b)


After End Effector has reached in front of the socket, we carry forward with the latching procedure.
This poses the challenge of rotation: The Socket might be tilted along any axis (x,y,z)

Rotation Around Z-axis:

![Screenshot from 2023-07-11 02-04-08](https://github.com/Pandey-utkarsh/JLR-Inter-IIT/assets/91661580/58f5ccea-8820-4ed6-b626-eeea89a5ea57)

![Screenshot from 2023-07-11 02-04-18](https://github.com/Pandey-utkarsh/JLR-Inter-IIT/assets/91661580/bab226b6-e64a-4669-a0d9-9c1b4107c728)


Rotation Around X, Y axis:
We used Monocular Depth Estimation. It is the task of estimating the depth value(distance relative to the camera) of each pixel given a single RGB image. It can be implemented with a simple RGB camera. Hence it saves the cost of using RGBD cameras.
![Screenshot from 2023-07-11 02-04-54](https://github.com/Pandey-utkarsh/JLR-Inter-IIT/assets/91661580/51ca28bc-7367-45ca-bca5-022c2c29d840)

![Screenshot from 2023-07-11 02-05-05](https://github.com/Pandey-utkarsh/JLR-Inter-IIT/assets/91661580/15e96ac0-eb32-48b4-8579-2b347db61e60)

