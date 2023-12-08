<h1>
    DATASET DESCRIPTION
    <!-- FairLabs Data Analytics Challenge<br> -->
</h1>
<p>
    This file contains a description of the dataset for the 2024 ADLM FairLabs Competition
</p>
<h3>
    Overview
</h3>
<p>
    The dataset is a real, de-identified clinical dataset consisting all patient encounters on the labor and delivery unit of a single, academic, tertiary-care center over a span of approximately two years, from 2/23/2027 to 3/12/2029 (actual dates were shifted to protect patient privacy). The quality improvement project went live on 03/21/2028 in this shifted timescale.
</p>
<p>    
    All results for first urine drug screens (UDS) per labor and delivery encounter are provided.
    At this center, peripartum UDS testing is performed using a mass-spectrometry based laboratory developed test.
    Additional features include the patient's self-reported race and whether or not a phone call was placed to Child Protective Services. A complete descipription of all columns in the data can be found below.
</p>    
<p>
    The data are all contained in this single comma-separated values called 'fairlabs_data.csv'. The data are in a wide format where each row represents a single labor and delivery encounter and the columns represent various features associated with that encounter (see column descriptions below).
</p>
<p>
    The use of this de-identified dataset for this competition has been reviewed and deemed as non-human research by the Human Research Protections Office at Washington University in St. Louis (IRB ID #xxxxxxx).
</p>    

<h3>
    Column Descriptions
</h3>
<dl>
    <dt>
        encounter_id
    </dt>
    <dd>
        Unique identifier of a single labor and delivery encounter
    </dd>
    <dt>
        delivery_date
    </dt>
    <dd>
        Date of delivery in shifted timescale
    </dd>    
    <dt>
        mother_id
    </dt>
    <dd>
        Unique identifier of an individual patient on labor and delivery
    </dd>    
    <dt>
        maternal_age
    </dt>
    <dd>
        Mother's age in years at the time of delivery
    </dd>    
    <dt>
        maternal_race
    </dt>
    <dd>
        Mother's race as reported in the Electronic Health Recorded
    </dd>
    <dt>
        uds_order_id
    </dt>
    <dd>
        Unique identifier of a single labor and delivery urine drug screen order
    </dd>
    <dt>
        order_indication
    </dt>
    <dd>
        Order indication provided by the ordering physician<br>
        Only available after the intervention go-live
    </dd>    
    <dt>
        uds_collection_date
    </dt>
    <dd>
        Date of urine drug screen specimen collection in shifted timescale
    </dd>
    <dt>
        detected_[compound]
    <dd>
        Urine drug screen result for [compound]<br>
        1: detected<br>
        0: not detected
    </dd>
    <dt>
        cps_reporting_date
    </dt>
    <dd>
        Date of reporting to Child Protective Services in shifted timescale
    </dd>
</dl>

