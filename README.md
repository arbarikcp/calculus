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
- For this takes take $\Delta{x}$ starting from 1.0 to reducing it to 1/1000
- ![alt text](images/week1-derivatives/der_10.jpeg)
- here as we see as the change in x goes to very small. the slope is going towards 2, which is 2 * 1  that correct, derivative of f(x) = $x^{2}$   is 2x.
- ![alt text](images/week1-derivatives/der_11.jpeg)

#### Derivative of Cubic function
- y=f(x) = $x^{3}$
- lets try to calulate manually the $\frac{\Delta{f}}{\Delta{x}}$ when x = 1.
- For this takes take $\Delta{x}$ starting from 1.0 to reducing it to 1/1000
- ![alt text](images/week1-derivatives/der_12.jpeg)
- lets calculate mathematically
- ![alt text](images/week1-derivatives/der_13.jpeg)
- as $\Delta{x}$  becomes very small , tends to 0. then the terms, 3x $\Delta{x}$ and $\Delta{x} ^{2}$ becomes 0. 
- derivative of f(x) = $x^{3}$ is 3 * $x^{2}$

#### Derivative of other power function
- let y=f(x) = $x^{-1}$
- Following the previous manual approach, lets find out the drivative of this function at x = 1.
- ![alt text](images/week1-derivatives/der_14.jpeg) 
- calculating mathematically 
-  ![alt text](images/week1-derivatives/der_15.jpeg) 

#### Derivative of Power function
- let y=f(x) = $x^{n}$
- ![alt text](images/week1-derivatives/der_16.jpeg) 

- Graphical tool for common derivatives: https://www.coursera.org/learn/machine-learning-calculus/ungradedWidget/fwPaZ/common-derivatives

### Inverse function
- A function `g` is called inverse of a function `f` if  g (f(x)) = x
- ![alt text](images/week1-derivatives/der_17.jpeg)
- Example: lets take a function f(x) =  $x^{2}$  and g(x) , its reverse function ,    g(x) = $\sqrt{x}$
- ![alt text](images/week1-derivatives/der_18.jpeg)
- **Derivative of the inverse function**: 
- in below example, we are trying to calculate slope at x = 1. Here we can see  $\Delta{g}$ = $\Delta{x}$  and  $\Delta{y}$ = $\Delta{f}$
- Slope of inverse function is 
-  ![alt text](images/week1-derivatives/der_19.jpeg) 
- **Example**:
- ![alt text](images/week1-derivatives/der_20.jpeg) 
#### Derivative of Trigonometric function
- ![alt text](images/week1-derivatives/SIn_1.jpeg)
- ![alt text](images/week1-derivatives/SIn_2.jpeg)
- for Sin function, f(x) = sin(x)
- If we try to see the slope of Sin(x) at various points like -$\pi$,-$\pi$/2 , 0, $\pi$/2 . it is -1, 0,1,0
- If we see the value of Cos(x) at these points then we will find that value of cos(x) is exactly same as slop of sinx.
- ![alt text](images/week1-derivatives/sin_der.jpeg)
- So we can say f(x) = sinx then $\displaystyle \frac{\partial f}{\partial x}$ = cos(x)

- Simillarly f(x) = cos(x) then $\displaystyle \frac{\partial f}{\partial x}$ = -sin(x)

- ![alt text](images/week1-derivatives/cos_Der.jpeg)
- for proof please check, https://www.coursera.org/learn/machine-learning-calculus/lecture/CcD2l/derivative-of-trigonometric-functions

### Euler's number (e)
- It is defined as (1 + 1/n)<sup>n</sup> , it is 2.718
- Its a special number if f(x) = $e^{x}$ then $\displaystyle \frac{\partial f}{\partial x}$ = $e^{x}$.
- So its derivative is itself only.

#### Understanding Euler's number
- you have $1. you have to deposit your money to bank to get intrests. among these 3 banks which one is better. and at the end of a year where your money will grow more.
- ![alt text](images/week1-derivatives/euler_1.jpeg)
- lets calculate
- ![alt text](images/week1-derivatives/euler_2.jpeg)
- ![alt text](images/week1-derivatives/euler_3.jpeg)

- What if a bank said if it will 1/12th of intrest for every month.
- ![alt text](images/week1-derivatives/euler_4.jpeg)
- at end of first month opur principal is (1 + $\frac{1}{12}$)
- at end of second month intrest will be 
$\frac{1}{12}$(1 +$\frac{1}{12}$).  So total principal at end of second month = (1 + $\frac{1}{12}$) + $\frac{1}{12}$(1 +$\frac{1}{12}$) =  $(1 + \frac{1}{12})^{2}$
- Like this at end of the year, it will become $(1 + \frac{1}{12})^{12}$

- Now if this interval reduced to small. with n equal intervals, then 
- ![alt text](images/week1-derivatives/euler_5.jpeg)

- If we reduced it to a very small number then 
- ![alt text](images/week1-derivatives/euler_6.jpeg)

- $(1 + \frac{1}{\infty})^{\infty}$  = e = 2.718
