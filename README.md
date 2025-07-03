
# Continuous Value Funding (CVF)

A novel mechanism for optimizing public goods funding by collectively graphing the expected value of incremental donations.



### The Problem: How Much to Fund?

Standard funding mechanisms (like direct donations or even Quadratic Funding) are excellent at identifying *which* projects have community support. However, they don't efficiently answer the next, critical question: **what is the optimal amount of funding a project needs to be successful?**

A $1,000 grant might be transformative for a small open-source library but completely useless for a team trying to build a new hardware prototype.

### The Solution: Continuous Value Funding (CVF)

CVF solves this by aggregating community wisdom to forecast a project's success at different funding levels. Instead of just donating, contributors are asked:

> *"Draw a curve showing how much of the project's total value you believe will be achieved as funding increases."*

These individual "value curves" are then averaged to produce a single, collective forecast that reveals where funding will be most impactful.

## How It Works: A Visual Explanation

The process is simple, intuitive, and powerful.

### Step 1: Elicit Individual Beliefs

Each participant draws a graph of their expectation. Some may believe in linear returns, others in diminishing returns, and some may see an "all-or-nothing" threshold.

![image](https://github.com/user-attachments/assets/1bfe4d02-24bc-4674-8fb6-b0d1b4b9bf40)


### Step 2: Aggregate to Find Collective Wisdom

The system averages all the individual graphs into a single, bold **Aggregate Opinion Curve**. This curve represents the "wisdom of the crowd" — our best collective guess at the project's funding-to-value relationship.

![image](https://github.com/user-attachments/assets/363b4043-5195-40a6-bdfd-9583d7c9b3af)

![image](https://github.com/user-attachments/assets/dd9b5620-6b5c-48c4-99bd-f5b2a351ff93)

### Step 3: Allocate Funds with Maximum Impact

The **steepest part of the aggregate curve** shows the "funding sweet spot." This is the range where each additional dollar provides the highest marginal value. A funding mechanism can use this information to allocate funds optimally, ensuring capital isn't wasted on projects that are already saturated or haven't yet met their critical threshold.

## Key Benefits

*   **Optimal Capital Allocation:** Directs funds where they will have the greatest marginal impact.
*   **Rich Data Signal:** Moves beyond a simple "donate" button to capture nuanced, expressive information from the community.
*   **Intuitive Interface:** Drawing a curve is a highly intuitive way for people to express complex beliefs about risk and return.
*   **Complementary to QF:** CVF can work alongside Quadratic Funding. QF finds *what's popular*, while CVF finds *how much to fund it*.

## Running the Simulation

This repository contains a Google Colab notebook (`Continuous_Value_Funding.ipynb`) to demonstrate the CVF mechanism.

1.  Open the notebook in Google Colab.
2.  Run the single code cell.
3.  The plots described above will be generated, illustrating the concept for both a simple "Lemonade Stand" and a complex "Rocket to Space" project.

## Potential Applications

*   **Gitcoin Grants:** Informing the allocation of matching pools to grantees.
*   **DAO Treasury Management:** Deciding on funding levels for internal initiatives or external grants.
*   **Venture Philanthropy:** Allowing donors to express beliefs about how a non-profit will use incremental funding.

## Contributing

This is a conceptual project, and we welcome contributions. Please feel free to open an issue to discuss new ideas or submit a pull request to improve the simulation.

## License

This project is licensed under the WTFPL License.
