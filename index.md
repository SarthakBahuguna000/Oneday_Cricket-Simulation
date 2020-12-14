
import os
import numpy as np
class Basic_outcome( ):
        wk=0 # wk is for wicket
        m=0 # m is for runs
        b=0 # b is used as a symbol for ball
        by=0 # by is for byes
        prob=0 # probability of runs
        n=300 # Total number of ball should be i.e b<=300
        v=1 # wide ball or no ball
        def simulation(self):
            for i in range(1,I):
                for j in range(1,J):
                    U= µ(1)i − µ(2)j +ε # Quality of the batsmen
                    output=''
                    for X in range(1,8):
                    # X is Total possible outcome
                    if X==1:
                        output='dismissal'
                    if X == 2:
                        output=0
                    elif X == 3:
                        output=1
                    elif X == 4:
                        output=2
                    elif X == 5:
                        output=3
                    elif X == 6:
                        output=4
                    elif X == 7:
                        output=6
                    # if bowl batted near a fielder
                    # Lets take it a
                    if µ(1)i > 0:
                        U=U+1
                    else:
                        U -=1

        # The probability of the outcome in ball depends upone Pijwbk
        def First_inin(self):
            s=0
            # There are 7 numbers of outcomes that can occur in each balls
            for b in range(1,n+1):
                p=input("What happened in this ball : Wicket /Runs / Extras(wide or Noball")
                if p=='Run' or p=='Runs':
                    score=list(map(int,input("Enter the score obtained in this ball : %d \n"  %i )))
                # score is the outcome of a  ball bowled
                    m=m+score
                elif p=='extras' or p=='Extras':
                        m=m+v
                        i=i-1
                else:
                    wk=wk+1
                    print('Out it is')

                if wk == 10 or i == n + 1:
                    break
                break
            print("Total runs of first innings are :%d" %m)

        def second_inin(self):
            s=m
            m=0
            for b in range(1,n+1):
                aggr = 0  # aggressivness of batsmen
                aggr = aggr + 1 if b >= 210 and b <= 300:
                    # probability of hitting six and giving away wicket increases


                p=input("What happened in this ball : Wicket /Runs / Extras(wide or Noball")
                if p=='Run' or p=='Runs':
                    score=list(map(int,input("Enter the score obtained in this ball : %d \n"  %i )))
                    m=m+score
                elif p=='extras' or p=='Extras':
                        m=m+v
                        i=i-1
                else:
                    wk=wk+1
                    print('Out it is')

                if wk == 10 or i == n + 1:
                    break
                break
            f=m
            if (f-s+1)/r> E1/E2:# E1 and E2 are resource ratio , r is resouce
                print("Second team wins")
            else:
                print('first team wins')



# Program is not in working condition but i tried to cover all the possible data





