# Lego_Trust_Game

[![IMG-1649.jpg](https://i.postimg.cc/fLZyVVwx/IMG-1649.jpg)](https://postimg.cc/jWgt9dn5)

#### you can find dataset [here on Kaggle](https://www.kaggle.com/mohammadnili/lego-trust-game)

## :game_die: Rule Table :
> [ (cheat/cheat) or (trust/trust) or (trust/cheat) or (cheat/trust) ] . [rewards or punishment]


               \          T2                C2
                \~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
                !          R2= +2   !           R2 = +3   !
            T1 !                   !                     !
              !   R1 = +2         !   P1 = -1           !
             ! ------------------!---------------------!
            !           p2= -1  !             p2 = 0  !
       C1  !                   !                     !
          !   R1 = +3         !    P1 = 0           !
          ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
## :gear: Game Init  :
  - Each player has :
  > A batch of lego slicea batch of colorful lego slices <br>
  > An score initialized to 0  <br>
  > List of movements initialized to empty   <br>
  - there is a common resource in the middle

## :video_game: :ski: Game plan : 
 In each steps , both participants hide one lego slice in one of their's hand secretly.  <br>
 Fist both hands bring them forward. <br>
 Simultaneously both players open one hand of their choice.
 
## Questions :question:
- When peaple Trust to each other and why ?
- Is gender a critical variable for Trust ?
   
 :chart_with_upwards_trend: :bar_chart: :chart_with_downwards_trend: Descriptive Analysis phase  :               
 - How kids trust ?
 > to adult <br>
 > to other kids     (this part by help of some friens for access to kids) <br>
                                
 - Is the first action of all humans "Trust" when confront a new person ? <br>
 
 Predictive Analysis phase :          
 - Is "Attention Bias" related to te Step_movment of each person ?
 - chategorize humans by Game_play of them and predict they presonality !!!                          

 ---------------------------------------------------------------------------------------------------------------------------<br>
 <p> We wanna show the tolerance of Trust /causality & correlation betweet Trust & other Table_feature </p>
 <p> search for confounding Variables /  and a hard work is simulating this trial for kids without changing game rule </p>
   ------------------------------------------------------------------------------------------------------------------------<br>
    > The rule of the Game : (cost of punishment & Rewards is different game by game) <br>
    > R1/R2 : (+1,+1)or(+2,+2)or... <br>
    > R1/P2 : (+3,-1)or(+) <br>
    > P1/P2 : (0,0)or(-1,-1,)or... <br>
