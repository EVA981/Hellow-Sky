PROGRAM hellow_sky
IMPLICIT NONE
CHARACTER(10) :: a = 'Hellow Sky'
INTEGER :: i
WRITE(*,*) 'Initiate hellow sky by entering 1, or enter 0 to end'
READ (*,*) :: i
IF (i==1) THEN
  WRITE (*,*) a
ELSEIF (i == 0) THEN
  GO TO 5
END IF
5 STOP
END PROGRAM
  
