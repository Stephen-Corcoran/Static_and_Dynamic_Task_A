### Testing task 1:

# Carry out static testing on the code below.
# Comment on any errors that you see below.

Note that we are only looking for errors here.

**Not** any issues with, i.e.: 
Thinking that methods should be renamed or should be class level, or using string interpolation etc. 

These aren't errors but rather standards that vary from developer to developer. 

Only comment on errors that would stop the tests running.

```python

class CardGame:


  def check_for_ace(self, card):
    if card.value = 1: # needs == as it is should be preforming a check = is for setting a value
      return True
    else # : needed
      return False
   

  dif highest_card(self, card1 card2): # def not dif probably a typo # , needed to between card1 and card2 
  if card1.value > card2.value: # lines 28 to 31 need to be indented
    return card #should be card1 to match line 27
  else:
    return card2
  


def cards_total(self, cards):# lines 35 to 39 need to be indented 
  total # should be total = 0
  for card in cards:
    total += card.value
    return "You have a total of" + total #needs to be f"You have a total of {total}"
  
```
