# FindMyLight
An intelligent system that uses crowd-sourced mobile sensor data to extract streetlight locations.

Based on the paper https://ieeexplore.ieee.org/document/9214128/

## What does it do?
While walking through the streets in night time, we notice that as we come closer to a streetlight, the light intensity increases when directly under it and decreases as we go away from it.
1) It collects ambient light sensor data continuosly in the background and stores it in a SQLite database.
2) These datapoints (in the SQLite DB table) are then converted into a CSV Sheet and then sent to a server.
3) We then apply the handmade clustering algorithm to extract the streetlight locations.

## To view our paper presentation video and pitch deck, click ![here.](https://drive.google.com/drive/folders/1AvtKcMVz8Hqv5drioP2NBINjGUBPnEnV?usp=share_link)


![image](https://user-images.githubusercontent.com/42934189/215974299-0f4f672a-8bea-4b8e-b5dc-8e3c45467628.png)

## Visualization of the clustering algorithm
![image](https://user-images.githubusercontent.com/42934189/215974432-97b77cff-18e5-48b2-bcc4-cdefe183db48.png)
![image](https://user-images.githubusercontent.com/42934189/215974471-2050e95c-8077-4de0-936c-a7f881b58f12.png)
![image](https://user-images.githubusercontent.com/42934189/215974512-cc4550dc-c0f8-42ab-a72f-c4ceadd47e32.png)
