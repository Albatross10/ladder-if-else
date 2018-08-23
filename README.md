# ladder-if-else
THIS IS THE OPTIONS i HAVE TRIED
trying to create a new variable from the biweekly assessment dataset following the indications on the email I sent you.

SHB1 <- ifelse(Biweekly_Assessmente_1_full$Q28=="0", 0, 
ifelse(Biweekly_Assessmente_1_full$Q28=="1",1, ifelse(Biweekly_Assessmente_1_full$Q28=="2",2, 
ifelse(Biweekly_Assessmente_1_full$Q28=="3",3, ifelse(Biweekly_Assessmente_1_full$Q28=="4",4, 
ifelse(5 < Biweekly_Assessmente_1_full$Q28 < 10,5,NA)))) )

SHB1 <- ifelse(Biweekly_Assessmente_1_full$Q28=="0", 0, ifelse(Biweekly_Assessmente_1_full$Q28=="1",1, ifelse(Biweekly_Assessmente_1_full$Q28=="2",2,
ifelse(Biweekly_Assessmente_1_full$Q28=="3",3, ifelse(Biweekly_Assessmente_1_full$Q28=="4",4, 
ifelse("5" >== Biweekly_Assessmente_1_full$Q28 >== "10",5,NA)))) )
