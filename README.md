<h1>
    FairLabs Data Analytics Challenge<br>
</h1>

<p>
    Welcome to the Third Annual ADLM Data Analytics Competition! 
</p>
<p>
    This year's competition is cohosted by the ADLM Data Analytics Steering Committee, the ADLM Health Equity and Access Division, the ADLM Informatics Division, and Washington University Section of Pathology Informatics. 
    <strong><u>A representative of the winning team will be invited to speak at the 2024 ADLM Annual Scientific Meeting with travel support and free meeting registration included</strong></u>.
</p>

<h2> 
    The Challenge
</h2>
<h3>
    <span style="color:gray"><i>Develop a Tool for Analyzing Fairness in Laboratory Testing</i></span>
</h3>
<p>
    This year's competition aims to develop novel tools for monitoring fairness in laboratory testing. 
    Competitors will be provided with a real de-identified clinical dataset documenting peripartum urine drug screening in the labor and delivery department of a single institution. 
    The challenge is to create a dashboard that analyzes and visualizes fairness using these data. 
    Solutions will be judged based upon functionality and adherence to best practices (see '<i>scoring</i>' section).
    Extra points will be awarded to teams that go beyond the dataset provided by engaging local stakeholders and applying their tool to analyze fairness in their own laboratory practice.
</p>

<h2>
    Context
</h2>

<h3>
    Fairness in Laboratory Testing
</h3>
<p>
    Laboratory testing carries benefits and unintended harms that are distributed unequally among patients. 
    Patients belonging to vulnerable subgroups often bear a disproportionate burden of harms while enjoying fewer benefits. 
    Inequities in Laboratory Medicine may be underappreciated due to limited real time monitoring in practice.
</p>
    
<h3>
    Peripartum Urine Drug Screening
</h3>
<p>
    Peripartum Urine Drug Screening (UDS) is an example of laboratory testing with benefits and unintended harms.
</p>    
<dt>
    Benefits
</dt>
<dd>
    Detection of specific compounds can be highly informative and guide immediate management decisions, as in the case of  opiate positivity leading to treatment of neonatal abstinence syndrome. 
    Additional benefits include the opportunity to provide counseling and support cessation efforts. 
    In other cases the clinical benefit is unclear, as in the detection of isolated cannabis positivity.
</dd>
<dt>
    Harms
</dt>
<dd>
    Peripartum UDS testing can undermine the mother's trust in the clinical team and lead to reporting to Child Protective Services (CPS), which can be traumatic and harmful to the new family.
</dd>
<p>
    A recent retrospective study performed at Washington University School of Medicine identified history of isolated marijuana use (IMU) as the most frequently cited indication for peripartum UDS<sup>1</sup>.
    They demonstrated that 99% of the positive UDS ordered for this indication were positive for cannabis only.
    The vast majority (89.8%) of mothers with a positive UDS ordered for IMU were reported to CPS.
    Of those mothers reported to CPS, 20.9% were White and 79.1% were Black despite only about 50% of mothers identifying as Black and positivity for a nonprescribed substance other than marijuana being 3 times more likely among White mothers.
</p>
<p>
    To try to address these inequities in UDS harms, a quality improvement initiative was developed.
    This initiative included revising the labor and delivery policies to prohibit ordering UDS for an indication of IMU.
    To promote accountability to these policy changes, an electronic question was added to the peripartum UDS order requiring the clinician select an appropriate testing indication. 
</p>
<p>
    <strong>
        Your task is to create a dashboard that can evaluate the impact of this quality improvement initiative by analyzing and visualizing the fairness of peripartum UDS testing over time.
    </strong>
</p>

<h2>
    Scoring
</h2>
<p>
    Competitors will be evaluated based on the functionality of their tool, their adherence to best practices for application development, and their ability to deploy their tool to address fairness in their local laboratory practice.
    Scoring will be performed by expert reviewers using a standardized scoring rubric and blinded to the competitor's identity.
</p>
<h3>
    Functionality (45 points)
</h3>
<p>
    There are many ways to conceptualize and quantify fairness<sup>2</sup>. 
    Points will be awarded for each concept that is correctly implemented. 
    Additional functionality points will be awarded for quality of visualization and user experience.
    
</p>
<dl>
    <dt>
        Implementation of fairness concepts (20 points)
    </dt>
    <dd> 
        Demographic parity (4 points)<br>
        Equalized odds (4 points)<br>
        Predictive parity (4 points)<br>
        Equal outcomes (4 points)<br>
        Other (4 points)
    </dd>
    <dt>
        Quality of visualizations (10 points)
    </dt>
    <dd>
        Impactful visuals (2 points)<br>
        Clean and appealing visualizations (2 points)<br>
        Axes and plots labeled (2 points)<br>
        Appropriate use of colors (2 points)<br>
        Appropriate sized fonts (2 points)<br>
    </dd>
    <dt>
        Statistics
    </dt>
    <dd>
        Confidence intervals provided for point estimates (2 points)<br>
        Formal hypothesis testing (3 points) 
    </dd>
    <dt>
        User experience (10 points)
    </dt>
    <dd>
        Intuitive navigation (5 points)<br>
        Interactivity (5 points)<br>
    </dd>
</dl>

<h3>
    Local activation (20 points)
</h3>
<p>
   Competitors are highly encouraged to identify local stakeholders that would utilize a fairness monitor in practice. 
   Points will be awarded for running the analytical tool on a local dataset. 
   Please provide a screenshot of your local analysis (without PHI) and a short letter from the end user documenting their engagement.
   Please summarize key findings from local activation.
</p>
<dl>
    <dt>
        Local data analysis (10 points)
    </dt>
    <dd>
        Local testing data analyzed for fairness (10 points)
    </dd>
    <dt>
        End-user engagement (5 points)
    </dt>
    <dd>
        End-user engages with fairness dashboard running on local data (5 points)
    </dd>
    <dt>
        Local insights (5 points)
    </dt>
    <dd>
        Describe insight provided by local analysis in 500 words or less (5 points)
    </dd>
</dl>



<h3>
    Best  practices (12 points)
</h3>
<p>
    Best practices in software development help to optimize quality, maintainability, and reusability. 
    Note that source code and commit histories are required to be eligible for points in this section.
</p>
<dl>
    <dt>
        Readability (4 points)
    </dt>
    <dd>
        Code is clearly and cleanly commented (1 point)<br>
        Code is simple and not bloated (1 point)<br>
        Code utilizes a clear and consistent naming convention (1 point)<br>
        Code is organized into hierarchy of modular functional units (1 point)
    </dd>
    <dt>
        Reusability (2 points)
    </dt>
    <dd>
        Code utilizes functionalized or object oriented programming (1 point)<br>
        Code can be configured to new dataset without modification of source code (1 point)<br>
    </dd>
    <dt>
        Version control (2 points)
    </dt>
    <dd>
        Version control system used to track development (1 point)<br>
        Commits are modular, logical, and appropriately scoped (1 point)
    </dd>
    <dt>
        Documentation and deployment (4 points)
    </dt>
    <dd>
        Usage notes provided (1 point)<br>
        Dependencies are defined (1 point)<br>
        Virtualized or containerized environment used (1 point)<br>
        Tool accessible through web hosting (1 point)
    </dd>
</dl>


<h2>
    Significance
</h2>
<p>
    The tools developed in this competition could be used more broadly to help laboratories to identify unfairness in laboratory testing and monitor quality improvement projects aimed to promote equity in laboratory practice.
</p>

<h2>
    Timeline
</h2>

<table>
    <tr>
        <th>
            January 15<sup>th</sup>, 2024
        </th>
        <td>
            Competition Begins
        </td>
    </tr>
    <tr>
        <th>
            May 15<sup>th</sup>, 2024
        </th>
        <td>
            Competition Ends
        </td>
    </tr>
    <tr>
        <th>
            June 15<sup>th</sup>, 2024
        </th>
        <td>
            Annoucement of Winning Team
        </td>
    </tr>
    <tr>
        <th>
            July 29<sup>th</sup>, 2024 (Anticipated)
        </th>
        <td>
            Presentation from Winning Team
        </td>
    </tr>
</table>


<h2>
    How to Participate
</h2>

<h3>
    Sign up for a GitHub.com account
</h3>
<ol>
    <li>
        Navigate to <a href='https://github.com/'>https://github.com</a>
    </li>
    <li>
        Click 'Sign up'
    </li>
    <li>
        Follow the prompts to create your personal account
    </li>
</ol>

<h3>
    Fork the competition repository
</h3>
<dl>
<ol>
    <li>
        Navigate to <a href='https://github.com/WUSM-LGM-Informatics-Section/adlm-fairlabs-competition'>https://github.com/ </a>
    </li>
    <li>
        Click 'Fork'
    </li>
    <li>
        Select 'Create a new fork'
    </li>
    <li>
        Set your GitHub account as the owner (defaut)
    </li>
    <li>
        Click 'Create fork'
    </li>
</ol>

<h3>
    Build your solution
</h3>
<ol>
    <li>
        Clone the forked repository<br>
        <span style='background-color:lightgray;padding:5px;border-radius:10px'>
            git clone https://github.com/myGitHubUsername/adlm-fairlabs-competition.git
        </span><br>
        Note: Replace myGitHubUsername with your GitHub handle
    </li>
    <li>
        Make a folder in the cloned repository with your team name
    </li>
    <li>
        Build your solution within your team folder
    </li>
</ol>

<h3>
    Submit your solution via a pull request
</h3>
<ol>
    <li>
        Navigate to <a href='https://github.com/myGitHubUsername/adlm-fairlabs-competition'>https://github.com/myGitHubUsername/adlm-fairlabs-competition</a><br>
        Note: Replace myGitHubUsername with your GitHub handle
    </li>
    <li>
        Click 'Contribute'
    </li>
    <li>
        Select 'Open pull request'<br>
    </li>
    <li>
        Click 'Create pull request'
    </li>
    Note: we will review your pull request to ensure that it contain everything needed to score your submission
    </li>
</ol>


<h2>
    Need Help?
</h2>
<p>
    If you are unfamiliar with GitHub, need help getting starting, or have other questions, please email mboyle@myadlm.org for assistance.
</p>

<h2>
    Reference
</h2>
<ol style="line-spacing:4">
    <li>
        Rubin A, Zhong L, Nacke L, Woolfolk C, Raghuraman N, Carter E, Kelly J. Urine Drug Screening for Isolated Marijuana Use in Labor and Delivery Units. Obstet Gynecol. 2022 Oct 1;140(4):607-609. doi: 10.1097/AOG.0000000000004930. Epub 2022 Sep 9. PMID: 36083598.
    </li>
    <li>
        Azimi V, Zaydman MA. Optimizing Equity: Working towards Fair Machine Learning Algorithms in Laboratory Medicine. J Appl Lab Med. 2023 Jan 4;8(1):113-128. doi: 10.1093/jalm/jfac085. PMID: 36610413.
    </li>
</ol>        
