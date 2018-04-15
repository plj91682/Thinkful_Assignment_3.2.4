# Thinkful_Assignment_3.2.4
(Prep Course) Unit 3, Lesson 2, Assignment 4

### DRILL - Exercises in Probability

1. Calculate the probability of flipping a balanced coin four times and getting each pattern: HTTH, HHHH and TTHH.
   -  According to the lesson, *Independent* probabilities can just be multiplied together __Intersection__
   ```
   The probability of two or more independent events can be calculated by multiplying the 
   probabilities of each individual event. The  
   probability of drawing a red marble and then a blue marble:
   ```
   Since flipping a __Balanced__ coin means the results are independent from coin-flip to coin-flip we can just multiply individual probabilities:
   
   P(H __∩__ T __∩__ T __∩__ H) = (0.5)^4 = 0.625
   
   Since we're dealing with indepedent events, flipping the pattern of __HHHH__ and __TTHH__ will be the same __62.5%__
     
2. If a list of people has 24 women and 21 men, then the probability of choosing a man from the list is 21/45. What is the probability of not choosing a man?
     - 100*(1 - (21/45)) = 53.3%
     
3. The probability that Bernice will travel by plane sometime in the next year is 10%. The probability of a plane crash at any time is .005%. What is the probability that Bernice will be in a plane crash sometime in the next year?
     - These are independent events, just multiply the probabilities together
     ```
      P(yearly-plane-crash-rate ∩ yearly-rate-you-will-fly-by-plane) = (0.00005 * .1) = 0.0000005
     ```
     
4. A data scientist wants to study the behavior of users on the company website. Each time a user clicks on a link on the website, there is a 5% chance that the user will be asked to complete a short survey about their behavior on the website. The data scientist uses the survey data to conclude that, on average, users spend 15 minutes surfing the company website before moving on to other things. What is wrong with this conclusion?
     - Website usage is not a normal distribution.  For example some users might land on the homepage and not click on any links for a long time.  
     
