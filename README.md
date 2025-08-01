# opencv를 활용해 QR인식하기
-pyzbar 코드 사용

# QR를 사각형 틀에 맞추기
-cv2.rectangle 코드 사용

# QR를 카메라로 인식하기
-cap = cv2.VideoCapture(0) 
-cv2.imshow('camera', img)
사용하여 카메라를 켠 후 QR 인식

# Aruco Marker를 이용한 위치추정
-거리를 통해 QR 인식
1. 카메라 파라메터(Camera parameter) 와 렌즈 왜곡(Lens distortion) 얻기
2. Aruco marker 생성
3. Aruco marker 검출
4. PnP(Persepective-n-Point)
