# Placements at IIT Delhi 2024

I sat for placements in 2024 at IIT Delhi. This is an attempt to compile the preparation I did from August 2024 to November 2024.

## Preparation:

### Competitive Programming (CP)

Graphs, trees, Dynamic Programming, recursion, and range queries are some of the most important topics. Some Sources of questions:

1. **Leetcode** [Profile](https://leetcode.com/u/anirudhakulkarni/)  
    Leetcode hard questions are important. Solving easy is a time waste. Some mediums are good but I regret not trying to focus on hard questions only as early as possible. Do not look at the solutions without solving for the sake of solving. I kept a target of 30 minutes per leetcode hard question until I gave up and saw the hint. Leetcode sheets are useful ways to get started: Striver, blind75, Neetcode150.  
   [Striver SDE Sheet - LeetCode](https://leetcode.com/problem-list/eeudwo2i/)  
   [neetcode.io](https://neetcode.io/practice).  
   Doing sheets is more than enough to clear all the tests. Leetcode premium question [data](https://docs.google.com/spreadsheets/d/1ilv8yYAIcggzTkehjuB_dsRI4LUxjkTPZz4hsBKJvwo/edit?gid=485397084#gid=485397084).

2. **CSES** [Profile](https://cses.fi/problemset/user/74593/)
   
   Most of the questions are good. This is probably good after leetcode. Difficult questions are good for practice. Some are [ridiculous](https://cses.fi/problemset/task/1160). This [video](https://www.youtube.com/watch?v=dZ_6MS14Mg4) motivated me.

3. [**cpalgorithms**](https://cp-algorithms.com/index.html) 
   
   This is the bible for algorithms. Data structures, graphs, and trees are a must. You will find the most minimal version of algorithm implementations here. But as I solved more and more questions from leetcode/cses/codeforces/tests I found myself going through 99% of the algorithms at least once.

4. **Codeforces**  
   Tests for HFTs sometimes borrow questions from codeforces 2000+ directly. I found dp on graphs questions from codeforces useful.

Some more advanced topics especially for HFTs include dp on graph and linear expectations questions on graphs.

### 2. Dev/C++

This is a very wide area. I felt having practical experience helps here. Some important topics one should consider in alphabetical order from my notes:

- Casting
- const
- constexpr
- constructors
- copy elison
- design patterns
- diamond problem
- exceptions
- fastio
- filesystem
- friend keyword
- inheritance
- iterators
- lambdas
- linux directory
- lvalue rvalue difference
- move vs copy
- operators
- padding and packing
- references
- signals
- smart pointers
- stack vs heap
- static keyword
- std::threads
- string
- templates
- virtual destructors
- vtable

I felt this was more than enough for what placement tests asked for. Practice gfg question sets like this <https://www.geeksforgeeks.org/commonly-asked-c-interview-questions-set-1/>, [C++ Programming Multiple Choice Questions - GeeksforGeeks](https://www.geeksforgeeks.org/c-programming-multiple-choice-questions/) occasionally. The more you solve better it is.

### 3. Quant Section

Probability is majorly required for quant profiles even though some SDE roles at HFTs also ask them as part of the general aptitude test. This includes probability and mathematical puzzles.

Xinfeng Zhou [datasciencecoursera/\[Xinfeng Zhou\]A practical Guide to quantitative finance interviews.pdf at master · geniayuan/datasciencecoursera (github.com)](https://github.com/geniayuan/datasciencecoursera/blob/master/%5BXinfeng%20Zhou%5DA%20practical%20Guide%20to%20quantitative%20finance%20interviews.pdf) and Heard on the street [cp_practice/Timothy-Falcon-Crack-Heard-on-the-Street_-quantitative-questions-from-job-interviews-Timothy-Crack-2003.pdf at master · pnjha/cp_practice (github.com)](https://github.com/pnjha/cp_practice/blob/master/Timothy-Falcon-Crack-Heard-on-the-Street_-quantitative-questions-from-job-interviews-Timothy-Crack-2003.pdf) are the gold standard for these questions. Many companies repeat the questions as it is from these books. Some sections such as option theory are not required. Mark Joshi also has some good questions to practice. 

Apart from this, I studied topics as I came across:

- Catalan numbers
- correlation
- covariance
- linear expectations
- p-value calculation
- sampling algorithms
- central limit theorem
- simulating probabilities
- random processes
- linear algebra in probability
- almost sure convergence

Some other questions I used but were not required as such are: <https://hireglyph.com/questions>, <https://www.quantguide.io/>, brainstellar, geeksforgeeks.

### 4. CS

This section is sometimes copy-pasted GFG questions or complex questions with an application of fundamental concepts. OS lectures from Sourav Bansal cover OS+parallel+some part of the architecture.

#### 1. CN

For Computer Network understand the layers. Understanding actual function calls instead of abstract ideas helped me in graviton interviews and interviewers seemed to appreciate it a lot. GFG problem sets are good for this.

#### 2. OS

<https://www.youtube.com/playlist?list=PLEAYkSg4uSQ3RTwDexX_T0TU7V9hHM_RO> this is the gold standard for OS with this <https://iitd-plos.github.io/os/2020/schedule.html>

#### 3. Parallel

I did not find any particular lecture series useful for this. Solving gfg questions and YouTube videos as required helped. Some of the important topics are semaphores, condition variables, threads, locks, etc. Try to apply these topics in practice. HFTs ask some really good questions in this area.

#### 4. Computer architecture

Again, occasional gfg questions and random slides from MIT help are here. NK hardware role asked for logic gates and constructing arbitrary truth tables from basic logic gates. Some important topics: Understand cache, cache coherence protocol, associativity, pipelining size calculation for page table etc. Someone else could contribute here.

From my experience, HFT SDE requires CS fundamentals, Dev/C++, CP extensively, and medium to high effort from the probability section depending on what roles you are being considered for.

Tech SDE requires CP, CS fundamentals, and a bit of Dev/C++.

HFT Quant requires CP, CS fundamentals, and quant section extensively. You could potentially just skim through CS fundamentals but still get through.

## Applications:

- Should I apply for just “important” profiles?

Getting experience with placement tests is important. I have seen people applying just for “important” profiles and not panicking in tests and not getting a single shortlist on day 1. I shamelessly applied for every profile out there. I experimented with time management and handling stress during tests. The same goes for interviews. I gave Tech SDE interviews as a mock for tech rounds and HR rounds.

## Placement Tests:

- Very few openings have CGPA requirements

- Placement tests are mainly CP. Being able to solve a random leet code hard within 30 minutes helped me to get through all of the tests. Few will require CS fundamentals and C++ as well (a must for HFTs). HFT quant will have additional quant sections as well.

- Most of the tests are quite straightforward with a similar pattern of 2 leetcode hard questions with 30 mins each and an MCQ section of CS fundamentals or CP fundamentals or a quant section.

- Some companies shamelessly repeat the questions: Refer to these sheets [Inter IIT Placements 2021-22 (google.com)](https://docs.google.com/document/d/e/2PACX-1vSDJ7BiVSUGaO6tDhv2kDeYDJnZ_TxuhTmg9loZIg6C-jlkfUdaJYdf5XasgbTgbOdDsm9ZK-udGamv/pub#id.bw56fwlrzzox), [Inter IIT Placement 2018-2019 (google.com)](https://docs.google.com/document/d/e/2PACX-1vRqsXE-Izz-qktbRKVexkt_eByPQQzaJ5vRKnd7gMClSINVRDF6tHJwXiVoz0NnJ-V9JamNaUvDEGou/pub), [2019-20 inter iit placement questions - Google Docs](https://docs.google.com/document/d/1I_N0dUs-SFqJ0E3v2bEZmIqmgCJr3fGD911Nd1En10s/edit#heading=h.36icyhqhrajp)

## Understanding Cultural Fit

This is usually a neglected part of placements. Try to understand the requirements of each profile beforehand. Understand the company culture and see where you fit beforehand. **Do not waste both your time and their time** in this process just to realize it's not the culture you want to join. **Avoid fancying any profile**. Understand the requirements of all profiles, what is fun to do, and what you can do. Stay away from firms with toxic work cultures.

1. **Across roles:**

   1. *Tech SDE* - great for someone looking for work-life balance or wanting to gain tech skills, depending on the firm’s culture. Some tech SDE jobs could require as little as 3 hours of work a day, and some could require as much as 12 hours.

   2. *HFT Quant* - No work-life balance. Be prepared to sit from 9:30 AM to 5-7 PM in the office, depending on load. High pay - some firms could be toxic depending upon HR, people in management, and seniors.

   3. *HFT SDE* - Same as HFT quant but workload could be a bit more lenient or harsh depending on firms and culture. Less pay after 4-5 years but more employable and less risky compared to HFT quant (Hire to fire?)

2. **Startup vs. established:**

   1. Established firms generally have better work-life balance. But relatively lower pay and lower workload. Have established cultures and access to industry pro people.

   2. Startups are usually high risk and high reward. More responsibilities and more workload. Usually great if you want to gain skills early in your career or if you want to startup in the future. It is easy to get exploited here.

## Interviews

- Interviews usually start well before day 1. Most of the HFTs will conduct multiple rounds before. Some Tech SDEs tried to conduct interviews this time, but OCS imposed restrictions.

- OCS restricts the number of interviews available on day 1.1 to just five interviews (petition to change this). You can select the preference a day before and get interviews slotted accordingly. I had all HFTs at the top and could not interview for any Tech SDE roles. You could be more strategic in filing the preferences to minimize the risk.

- Having a friend with your phone handling interview scheduling can be useful. Companies tend to overshoot the time limit if they like you, and you can easily miss other interviews. You can prioritize beforehand which one to focus on and which one to skip to avoid any miss on day 1. I skipped the final round for some of the profiles to continue with rounds for prioritized profiles.

- Interview prep: Most of the prep is done while doing the tests. There is nothing to do here but reduce stress and be confident. Give some mock interviews with friends, seniors or anyone who can ask you a leetcode question and judge your response.

1. **CV** - be ready to explain internships and projects, highlight achievements etc

2. **Live coding** - common with tech SDEs

3. **Puzzles and quant questions** - common with HFTs both tech and quant

4. **HR** - be ready with cultural fit questions why do you want to join us etc

5. **Dress well** - plan your haircut well in advance to avoid last minute embarrassments

## After Interviews

- Not getting what you wanted in the placements is not the end of the story. There will be some openings that weren't available during placements. Approach seniors to check if openings are available.

- Some startups are great yet they don't get a slot at IITs - approach them

- Some firms will approach you after the interviews once you get an offer from competitors ready to match or hike up whatever is being offered.

- I have seen people not solving a single question in on-campus placement tests and yet approach them after placements and bag an offer. **Caution: This does not work with all companies**, so be prepared for being embarrassed if you do so.

## A Side Note

- Placements are stressful. It is very easy to be worn out. Given the current market situation, it is easy to panic/get depressed. IITs usually see several suicides during this phase. Make sure to create a support system with friends, and reach out to counselors.

- Optimize health - staying active physically, and taking frequent breaks helped me optimize my performance

## Some More Prep Links

1. [C++ Coding Standards: 101 Rules, Guidelines, and Best Practices](https://micro-os-plus.github.io/develop/sutter-101/)

2. [Spring 2015 -- Computer Architecture Lectures -- Carnegie Mellon - YouTube](https://www.youtube.com/playlist?list=PL5PHm2jkkXmi5CxxI7b3JCL1TWybTDtKq)

3. [MIT 6.824 Distributed Systems (Spring 2020) - YouTube](https://www.youtube.com/playlist?list=PLrw6a1wE39_tb2fErI4-WkMbsvGQk9_UB)

4. [Arithmetic Game – Online Speed Drill](https://arithmetic.zetamac.com/game?key=a7220a92)

5. [Sparse Table and Fenwick Tree (Binary Indexed Tree) \[CodeISM 2023\] - YouTube](https://www.youtube.com/watch?v=ecJDSQov5eA\&list=PL40a3hTWsqXBFAKwLv-02tsKOLCud6hvf\&index=13)

6. [Full Interview Preparation Cheat Sheet... This will save a lot of time. found this to be really helpful. Hope you also gain benefit from these resources.](https://www.reddit.com/r/cscareerquestionsEU/comments/zesdg8/full_interview_preparation_cheat_sheet_this_will/)

7. [(16) Discord](https://discord.com/channels/996058498657960006)

*PS: After endless Pros & Cons Jams, I finally ended up joining Quantbox Research Capital as Dev.*
