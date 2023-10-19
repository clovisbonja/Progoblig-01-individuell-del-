# Progoblig-01-individuell-del-
whitebase = rectangle(300, 200, "solid", "white")        
redsquared = square(80, "solid", "red")
redrectangle = rectangle(180, 80, "solid", "red")
bluerectangle1 = rectangle(20, 360, "solid", "blue")
bluerectangle2 = rectangle(520, 20, "solid", "blue")


put-image(redsquared, 40, 40,
  put-image(bluerectangle1, 100, 180,
    put-image(redrectangle, 210, 160,
      put-image(redrectangle, 210, 40,
        put-image(redsquared, 40, 160,
          put-image(bluerectangle2, 40, 100,
            whitebase))))))