Problem 1] Number of grains of rice on the 100th day

Create a code to calculate how many grains of rice you receive in total on the 100th day, and output the answer. Also, use a line graph to represent the change in the number of rice grains you receive on that day and the total number of rice grains you receive by that day from day 1 to day 100. (The vertical axis is the number of rice and the horizontal axis is the number of days)
【Problem 2] Number of rice grains outside of the 100th day

The number of days in this anecdote is ambiguous, such as 30 days or 81 days. Let's create a function that takes days as an argument so that it can handle any story. After creating the function, please answer how many rice grains you will receive in the number of days you take the course. Please output the line graph as well as problem 1.

The following template contains not only the framework as a function, but also comments on arguments and return values. Please refer to it and rewrite the comments in a way that is easy for you to understand.

《Model》
def compute_sorori_shinzaemon(n_days=100):
    "" "A function that calculates the number of rice grains per day in the rice anecdote of Shinzaemon Sorori.

    Parameteres
    -----------
    n_days: int
        Number of days to get rice (default : 100)

    Returns
    -------
    list_n_grains : list
        List of the number of rice you get one day (list length equals n_days)
    list_total_grains : list
        List of total number of rice received by a certain day (list length is equal to n_days)
    """

    # Write the code here. pass is an instruction that means do nothing.
    pass

    return list_n_grains, list_total_grains

list_n_grains, list_total_grains = compute_sorori_shinzaemon(n_days=10)

【Problem 3] How many people can live for how many days with the rice we get?

Create a function to calculate how many people can live for how many days with this rice. Output how many days the number of people in this class can live with the grains of rice they receive for the duration of the course.

The minimum input for the function is the number of rice grains (int) and the number of people(int), and the output is the number of days to live (int). Please make sure that the function name and comments are easy to understand.

The number of grains of rice needed per day is not provided here. Please do your own research and put it into a formula. Please leave a comment on how you did your research and what you used as your basis.
