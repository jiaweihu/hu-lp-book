# Objectives, Decision Variables, and Constraints

In this video, we'll discuss the three components of optimization problems. Objectives, decision variables, and constraints. And we'll see how these come together in order to help you make the right trade-offs, strike the right balance, and figure out the optimal solution to your problem. When you set out a problem which is extremely complex has many variables and many details that you need to consider many options that you have. It's often useful to build a model to represent this real world system. A model represents the essential features of an object, system, or a problem in the real world, leaving out the trivial, unimportant details. And the model helps you focus in and zoom in on what's really important and what can be ignored. Models help you model the real world. Models are extremely useful because you can then analyze and manipulate the variables in the model, the inputs to the model and the different dependencies of the model to give you insight into how the real system might behave under all of these different conditions. You can see if you change a particular input, what the corresponding change in the output will be. Now doing this in the real world is difficult. Models are cheaper, faster, and safer than constructing and manipulating real systems.
And this is why when you have an optimization problem, then you have to make decisions by making the right choices for trade-offs and for all of the other variables, it helps to have an optimization model. Optimization models are mathematical models that help you find the best solution with respect to some evaluation criterion that you specify. I want to maximize the profit. I want to minimize the time taken. For any optimization problem, there might be any number of solutions. Not all of those solutions will be ideal or the best solution, but they are all feasible solutions. So the best solution for your particular model which models your particular situation or problem, is chosen from a set of alternative solutions. And these alternative solutions are referred to as feasible solutions which together form the feasible solution set. What are these feasible solutions? A feasible solution is defined by a set of mathematical constraints, which are mathematical inequalities. We've discussed that optimization models are important. They are really needed because resources in the real world are scarce, and resources have to be well allocated.
These scarce resources are modeled as constraints which are mathematical inequalities ensuring that you only use as much resource as is available. So any optimization model which functions under a set of constraints are known as constrained optimization models. These constraints represent the scarcity of the various resources that you use in solving the problem. It's not possible for you to use more resources than available to solve a problem. And all of the feasible solutions use fewer resources than available. They operate under these constraints. We'll be working with constrained optimization models because nothing in the real world is unconstrained. Resources are always scarce. So within a constrained optimization model, let's look at three important components. The first component has to do with what is it that you're trying to achieve? Are you trying to maximize revenues? Do you want to maximize profit? Do you want to maximize efficiency? Do you want to minimize time? Do you want to minimize costs? These are statements for, what your end goal might be? What do you want to achieve?
Next, you have to think of what is it that you actually control. Now, what are the variables that you can tweak to achieve your objectives? What are variables that are fully in your control that can be changed by you? What you control is what you can manipulate in order to achieve your end goal? And finally, you need to think about what scarce resources that you might need to use in order to achieve what you want? In order to get to your goal of profit maximization or cost minimization, what are the scarce resources that you need to use? Resources can be in terms of number of people, money, plant capacity, anything. What you're looking to achieve has a formal name. This is referred to as the objective function. And the objective function is something that you seek to either maximize or minimize. If it's something like revenues or profit, you'll seek to maximize the objective function. If it's a cost or time, you'll seek to minimize the objective function. What is in your control? Those are the decision variables. Decision variables typically refer to how much you produce? How many units of a particular widget? How many cars? How many hours do you run your machinery? How many people do you employ? All of these can be decision variables.
And finally, the scarcity of resources is modeled using constraints. What are constraints that the real world applies on your solution? You may be limited by time, money, natural resources, engineers, salespeople, anything. When you're framing your optimization problem, you need to answer these three questions. These questions are all important. The questions are what are you looking to achieve? What are the variables that you control? And what scarce resources do you need to achieve your end goal? The answers to these questions make up the fundamental building blocks of your optimization problem. And these are what you need to frame the problem. Optimization forces us to mathematically model the answer to each question. Each of the individual components the objective function, the decision variables and the constraints are represented mathematically. And the answers to the questions make up the optimization problem.
Let's dive deeper into each component of the optimization problem, starting with the objective function. Now, the objective function is the criterion that we are using to evaluate the solution. How do we know that we have obtained our solution and this is the best possible one? The objective function is a mathematical function that involves the decision variables. So, all of the decision variables, the values that you control are part of the objective function and this function should be numerically evaluated. You should be able to get a number as the result. Now the objective function also specifies the direction of the optimization. Do we want to maximize the objective function or minimize the objective function? Do we want to maximize profit or minimize costs or objective function can be a maximization problem or a minimization problem? Next, let's move on to the decision variables. Now, these are physical quantities or units that are controlled by the decision maker, us. And these represent unknowns in your equation. We don't know them upfront. These unknown variables are decision variables can represent the number of widgets that you produce, the number of machines that you use to perform the various operations, the marketing budget that you assign for this particular activity, and so on.
The output of the optimization is an optimal value for all of these decision variables. We are looking for the best value for these decision variables to achieve our objective function. The need exists for optimization because resources are scarce and resources are represented using constraints. These are functional equalities or inequalities. And they can represent physical, technological, legal, ethical, capacity, time, and any other restriction. Any restriction or constraint imposed by the outside world that we cannot control that we have to operate within is represented by these constraints. Now, these are restrictions that are defined on our decision variables. You can only produce so many units because that's what this plant has the capacity for. That is a constraint. A solution to the optimization problem is a feasible solution only if it satisfies all of the constraints that you have set up on the decision variables. And the optimal or the best solution is found from amongst these feasible solutions.
Let's quickly see why optimization models are so useful. Optimization models help us structure our thought process because they force us to mathematically pin down our objectives, our constraints, and our decision variables. They help us make decisions in an objective manner rather than in a subjective manner. Real world problems often tend to be arbitrarily complex and models allow us to gain a handle on this complexity. Optimization models make complex problems tractable. Setting up a mathematical optimization models allow us to harness the power of compute to discover solutions rather than working out the solutions by hand. You can simply feed it into a computer. There are libraries which help us solve these models and they facilitate "what-if" analysis you can tweak variables and see how the result changes. However, you need to keep certain caveats in mind when you use an optimization model. Remember the formulation of the model is extremely important. If you set up your model wrong, you'll end up solving the wrong problem and there is nothing that will prevent you from doing that. It's up to you. And finally, models do not account for qualitative criteria in evaluating decisions, only quantitative criteria. So, the model's optimum need not be the real-world optimum and this is an important detail that you need to keep in mind.
