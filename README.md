# Calculus

## Motivation to Derivative
- Lets take an example of a vehicle. it starts with some speed, then it moved to higher speed, the stopped for sometime, then moved in a lowerspeed. After an hour it reached some distance. If I want to calculate **velocity** , 
    - v = $\frac{\Delta{s}}{\Delta{t}}$
    - change in distance/change in time.
- Here we are calculating velocity after an hour interval.
- But If I want to calculater velocity at any point in time instance.thats is called **instatanious velocity**
- **Derivative** is the instantaneous rate of change of a function, Here the function is dinstance and derivative is velocity.

- Suppose you have a dataset of time and the distance travelled by that time. Each time is in interval of 5 second. Can you find velocity at exactly t = 12.5 seconds.  
    - No, minimum velocity we can find is in interval of 5 seconds. 
    - We can find the average velocity from 10 to 15 seconds.

#### Slope
- at time 10 suppose the car is at 122m. then at time 15 it is at 202. Velocity is same as calculating slope on the line.
![alt text](images/week1-derivatives/slope.jpeg)

#### Derivative and tangents.
- Suppose we have a function how the car moved with respect to time. now we want to calculate what is instantaneous velocity at time 12.5.
- Lets start with  by calulating velocity between 2 points, first point is 12.5second other one is some other point. But that is not the velocity at time 12.5. 
- Lets reduce the distance. 
- ![alt text](images/week1-derivatives/der_1.jpeg)
- If we reduce the distance to a very minimum, then the slope becomes tanget line.
- ![alt text](images/week1-derivatives/der_2.jpeg)
- Instantaneous rate of change is when we move atiny tiny bit of distance in tiny bit of time.
- ![alt text](images/week1-derivatives/der_3.jpeg)

**ZeroSlope**: When the function (distance) didn't change in a tiny interval of time. thenthe slope is 0. 
- Below is a graph of a car's distance with respect ti time. At these 4 positions t = 10, t = 16, t= 22, t=34 car's velocity is 0. at that point derivative is 0 as there is no change in distance for a tiny t.
- ![alt text](images/week1-derivatives/der_4.jpeg)
- **Maxima** is the point where car travelled to maximum distance from origin. in this example it is at t = 10.
- **Minima** is th epoint where car travelled to a minimum distance from a origin. in this example it is at t = 34.
- In any continuous function , maxima and minimam occurs at point where slope is 0. derivative is 0. 

- Graphical tool for derivative and slope: https://www.coursera.org/learn/machine-learning-calculus/ungradedWidget/CwsqD/concept-of-derivatives
- Graphical tool, approximation of derivative:  https://www.coursera.org/learn/machine-learning-calculus/supplement/AOCfq/approximation-of-derivatives

#### Notations:
- ![alt text](images/week1-derivatives/der_5.jpeg)
- As we always plot the graph in x and y axis. this will be 
- ![alt text](images/week1-derivatives/der_6.jpeg)
- In general we write it as a function y= f(x)
- ![alt text](images/week1-derivatives/der_7.jpeg)


### Common derivatives
#### Derivative of a constant function.
- `y= f(x) = c`
- if it is a constant function then there is no slope at all. its derivative is 0.
- ![alt text](images/week1-derivatives/der_8.jpeg)
#### Derivative of a line.
- `f(x) = ax + b`
- In this case slope of the line is **a**. 
- SO the derivative at any point will become **a**.
- ![alt text](images/week1-derivatives/der_9.jpeg)

#### Derivative of Quadratic function
- y=f(x) = $x^{2}$
- Derivative is the rate of change of f for a tiny change of x.
- lets try to calulate manually the $\frac{\Delta{f}}{\Delta{x}}$ when x = 1.
- For this takes take Delta{x} starting from 1.0 to reducing it to 1/1000
- ![alt text](images/week1-derivatives/der_10.jpeg)
- here as we see as the change in x goes to very small. the slope is going towards 2, which is 2 * 1  that correct, derivative of f(x) = $x^{2}$   is 2x.
- ![alt text](images/week1-derivatives/der_11.jpeg)