START
    INPUT num
    SET a = 0
    SET b = 1  
 WHILE num > 0
        IF num % 100 = 90  
            SET a = a + 9 * b
            SET num = num / 100  
            SET b = b * 10  
        ELSE
            SET a = a + (num % 10) * b 
            SET num = num / 10  
            SET b = b * 10  
        ENDIF
    END WHILE

 PRINT b
END






![IPO](https://github.com/user-attachments/assets/9b5d5858-10fa-4640-a7d1-104d14c19a4a)
![Flowchart](https://github.com/user-attachments/assets/aa51e3ef-e080-4549-a7b8-93c8f4496951)
