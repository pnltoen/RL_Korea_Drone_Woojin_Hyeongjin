실행
mlagents-learn "C:\Users\Park woojin\Desktop\ml-agents-release_18\config\ppo\5_pnltoen.yaml" --env="C:\Users\Park woojin\Desktop\2021_RLKR_Drone_Delivery_Challenge_with_Unity-master\DroneDelivery.exe" --run-id=Day4_Drone_pnltoen(PPO) --no-graphics

텐서보드
tensorboard --logdir="C:\Users\Park woojin\results"

텐서보드 할 때 이렇게 해야 나머지 비교하면서 볼 수 있어 그래야 튜닝하기 편함
