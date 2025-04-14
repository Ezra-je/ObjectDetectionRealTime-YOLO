# Developing High-Throughput, Low-Latency Visual Perception Systems Leveraging YOLO Architectures for Real-Time Object Localization

HOW TO USE

for photos:
python yolo.py --image (your file) --yolo yolo-coco

example:
- python yolo.py --image images/a.jpg --yolo yolo-coco
- python yolo.py --image images/baggage_claim.jpg --yolo yolo-coco
- python yolo.py --image images/living_room.jpg --yolo yolo-coco
- python yolo.py --image images/soccer.jpg --yolo yolo-coco

for videos:
- python yolo_video.py --input videos/airport.mp4 --output output/airport_output.avi --yolo yolo-coco
