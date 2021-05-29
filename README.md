
Import cv2
Cam = cv2.VideoCapture(1)
While cam.Isopened():
     ret, frame = cam.read()
     If cv2.waitkey(10) == ord('s'):
     break
Cv2.imshow('Granny cam', frame)
