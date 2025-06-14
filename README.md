# 🌳 스마트팜 SmartFarm
>
> 스마트팜
>
># 📄프로젝트 정보
>
> 센서 활용을 통한 데이터 수집
>
>자동 모니터링 환경 구축
>
>설비 연동 제어
>
>> ### 📅제작기간 Development Time
>
>>2024.12.01 ~ 2024.12.09


> ### 🧑‍🤝‍🧑참여 인원 Number of Participants
>
>> 본인 포함 5명

>> 5 people including myself
>>
>> 
> # 🔀모델 및 구상도 System Block Diagram
>
>![image](https://github.com/user-attachments/assets/a3842d82-fdb1-42b0-b1a7-6f4f51a27fe5)
>
> ## 🔌프로젝트 결과
>
> # 회로도
>> ![image](https://github.com/user-attachments/assets/f61e9395-f7da-498d-a80a-2ad314a9b066)
>
> # esp32 코드
>>![image](https://github.com/user-attachments/assets/50c0e20a-53f7-4cdf-9e59-5259f4c47fa0)
>HtTP요청, 센서데이터를JSON 형식으로 응답
>
>![image](https://github.com/user-attachments/assets/ef6c3953-fc1c-4b18-b64e-f71932cfa108)
>클라이언트로부터 받은 HTTP 요청을 수신하고 버퍼에 저장
>
>![image](https://github.com/user-attachments/assets/4beb9946-8941-47e2-8665-127b7bbcd3b7)
>데이터 파싱
>
>![image](https://github.com/user-attachments/assets/9036dccf-5a32-4992-b0c3-f3c1d6a8e056)
>URL 경로 정의
>
> # NODE-RED 코드
>
>![image](https://github.com/user-attachments/assets/3a38e244-de14-45e2-a4bf-2fd393e7bfdf)
>대시보드에서 전달된 값들과 센서값 가져오기
>
>![image](https://github.com/user-attachments/assets/c8a53e8e-8c8a-4864-bd75-0e97da61688b)
>스캐줄러 모드 > 자동 / 수동모드
>
> # STM32 코드
>
>![image](https://github.com/user-attachments/assets/31cc9d6d-5c11-4f00-b091-cdf3fd25ec20)
>제어상태 수신
>
>![image](https://github.com/user-attachments/assets/438ae484-f0d6-4aeb-b8e1-72b10d918c71)
>센서 데이터 송신
>
> # 외관
>
>![image](https://github.com/user-attachments/assets/ec24def2-4282-4343-82eb-c44fdf4058fc)
>
>![image](https://github.com/user-attachments/assets/c180f2bd-74cb-4fa1-b10e-8356cb01a091)
>
> # 대시보드
>
>![image](https://github.com/user-attachments/assets/48dd646a-449f-4e8d-97ab-58adada52ddd)
>센서값 실시간 모니터링, 현재 제어 상태 모니터링, 최근 경보이력 표시, 실시간 CAM확인
>
>![image](https://github.com/user-attachments/assets/9fdce9af-5f9e-4bc3-9fb5-300b651510f8)
>실시간 센서값/조명 밝기 현재색상, 액추에이터 설비제어- 스케줄러, 설비제어- 송풍/배기/펌프 자동 수동제어, 설비제어-LED 밝기와 섹상제어
>
>![image](https://github.com/user-attachments/assets/2ee0f6b5-44d2-49ab-b684-ca511f9cef5e)
>실시간 스트리밍 화면, 과거 촬영된 사진 조회
>
>![image](https://github.com/user-attachments/assets/7dbd1c10-ff0c-4df1-bc63-6e6da82f916f)
>외부 온습도 그래프, 수위센서/토양습도 그래프, 과거 경고 조회




