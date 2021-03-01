# Multiverse Module 1  
  
## Meeting  
  
* Presenter  
    * Harry Gulliver  
    * Francesca Capetta  
* 25 Feb 2021  
    * 09:30  
  
## Data Life Cycle  
  
* Steps for a piece of data  
    * Creation  
        * structured or unstructured  
        * quantitiative or qualitative  
        * what is the source  
        * reliability  
        * size  
        * discrete or continuous  
        * how can it be accessed  
    * Storage  
        * Where and How  
        * Rules  
        * Catalog  
    * Usage  
        * NOT PART OF THE BCS LIFECYCLE  
        * internal or external access  
        * business rules govening usage  
        * what other use cases could be applied  
        * varied or routine usage  
            * automation  
    * Archival  
        * Needed now or can they be archived  
        * is the working life long or short  
        * will the data be made availab le given prior notice  
    * Obsolesence  
        * How long is it since someone used this data  
    * Deletion  
* Activity  
    * New Idea  
        * walk through the lifecycle  
        * Incident  
            * Creation  
                * tooling  
                    * HPOM, DarkTrace  
                    * triggers  
                * service desk  
                    * calls, SM9  
                * SI tooling  
                * structured and unstructured  
            * Storage  
                * tooling for the databases  
                * but commentary / resolution data?  
            * Usage  
                * aggregation  
                * presentation  
                * drill down  
                * root cause  
                    * patterns  
                * Account team, Client review boards  
                    * Improvement  
                    * RCA  
                    * Demonstrate complaince  
                    * benchmark against other accounts  
            * archivial  
                * unknown  
                    * for tools, there probably is none  
                    * may timeout and throw away data older than some horizon  
                * most data presumably times out after resolution  
                    * but trend spotting?  
                    * contractual records?  
            * Obsolsence  
                * as archiving  
            * Deletion  
                * see archiving... :D  
    * Is it actually a cylce  
  
## Data Analytics Life Cycle  
  
* Plan  
    * What is the outcome  
* Data Preparation  
* Analysis  
* Modelling  
* Refine and Compare  
    * Train/Test split  
        * split the data 80/20  
            * use 80 to train the algorith  
            * 20 to test  
* Communicate and Implemnet  
* Exercise  
    * is there a bias about unposted salaries  
    * what types of data might we collect  
        * location  
        * other benefits  
        * industry / company  
        * skills requested  
        * length of experince  
        * type of company  
            * startup  
        * number  
            * infer demand  
                * for Data   
                    Analuysts  
  
                * or wider roles  
    * where does that data come from  
        * job sites  
            * linkedin  
            * monster  
        * company sites  
        * glass door  
    * over time  
        * jobs that get re-posted  
            * (e.g. unfilled)  
        * salary trends  
            * over time  
            * by region  
    * other research  
        * feedback  
* Setting a Hypothesis  
    * Two Types  
        * Null  
            * Assume whar yoiu are investigating is false  
            * nothing is happening  
            * H0  
        * Alternative  
            * Someting is happening  
            * assumes what you are invesitgating is true  
            * H1  
    * frequentise statistics  
        * frequentist vs bayesian  
  
## Communication and Dealing With Stakeholders  
  
* Identifying Stakeholders  
    * How to manage  
    * how to comunicate  
    * Who  
        * anyone who is impacted by the project  
* Types of question  
    * Explorative  
    * Affective  
    * Probing  
    * Analtical  
    * Clarification  
* Factors to consider  
    * what return?  
    * what is their opinion of you  
    * who influences them  
    * what are their goals  
    * what do you need from them  
    * what do they want / need from you  
  
## Key Terminilogy  
  
* Requirements Elicitation  
    * Apprenticing  
        * get them to teach you, then try it yourself  
    * Observing  
        * watch them do it  
    * Recounting  
        * retrospective  
    * Enacting  
        * Recreate the task and observe  
        * do it yourself  
    * Using Documents  
* Types of knowledge  
    * Tacit  
        * gained through experience  
        * subjective  
        * insights  
    * Explicit  
        * can be codified  
  
## Validation vs Verification  
  
* Verification  
    * checking against some requlation or requirmeent  
* Validation  
* Not the same as Data Validation or Data Verification  
  
## Notes  
  
* histogram  
    * a contionuous axis split into discrete bins  
* bar chart  
    * underlying data is discrete  
* Verification  
    * Verity  
        * Truth  
  
## Data Types  
  
* Qualitative  
    * Discrete  
        * usually integer, but not always  
        * BCS: Categorical  
    * Continuous  
* Quantitiative  
    * Binomial  
        * two names"  
            * two categories  
            * usually TRUE, FALSE  
    * Nominal  
        * more than two categories  
    * Ordinal  
        * where there is some sort of ordering, but not numerical  
  
## Project Briefs  
  
* Project Sponsors  
    * what do you need to ask them  
    * do they understand garabe in garbage out  
* Template  
    * Brief Title  
    * situation  
        * Relevance  
        * ...  
  
## Data Sources  
  
* Types of source  
    * Public Data  
        * Open Data  
            * has some provenance  
                * well maintained  
                * reputable sources  
                * likely to be  
                    * structured  
                    * licenses  
                    * up to date  
                    * cleaned  
            * a subset of public data  
        * anything in the public domain  
    * Internal / Company Data  
        * Operational Data  
        * Administrative Data  
            * about running the day to day operations  
    * Client Data  
        * another companies proprietary data  
    * Third Party / Purchased Data  
    * Research data  
        * generated for original research  
            * observational  
            * simulation  
            * derived  
* Consider about sources  
    * accuracy  
        * is it trustworthy  
        * up to date  
        * relevance  
    * limitations  
    * compatability  
    * legal and regulatory rights to use  
    * context  
  
## Data Protection Act  
  
* Considerations  
    * Data MUST be kept secure  
    * store data must be relevant  
        * some reason for keeping it  
    * kept no longer than necessary  
    * accurate and up to date  
    * obtained and processed lawfully  
    * processed within the data subject's rights  
    * obtained for specified lawful purposes  
    * must not be transferred to countries without adequate data protection laws  
* based on 1998  
    * not yet updated to 2008  
    * but is BASED on 1998  
* Personal Data  
    * anything that can be used to identify an individual  
        * unique, idenfifyable, living human being  
    * or be about that individual  
    * does not cover deceased  
  
## Data Formats  
  
* Structures  
    * Unstructurerd  
        * Cannot be directly procesed  
    * Semi-structured  
        * for the exam, if it isn't 100% structured, then consider unstructured  
        * may depend upon the context / framing of what you're attempting  
            * thinking about data management systems  
    * structured  
  
## ETL  
  
* Data Warehouse  
    * Extraction  
        * Data is copied, not moved  
        * usually data validation happens here  
            * structure  
            * format  
            * permissions  
        * continous or batch  
    * Transformation  
        * apply changes to the copy  
            * source data remains unchanged  
    * Load  
        * Verification when loaded  
        * compare to source  
            * compare to truth  
    * should be static data  
        * e..g not transactional data  
        * move once it becomes historical  
* Data Lake  
    * how to transform unstructured data to fit a specified scheme  
        * extract and load as is  
        * transform when used  
            * specifically for that use  
        * i..e throw the data in as it arrives  
            * then worry about structuring it on use  
    * ELT  
        * Extract, Load, Translate  
* Data Validation  
    * Does the data conform to some constraints  
        * e.g. ages are an integer  
        * not checking that its actually true  
* Data Verification  
    * how true / correct is the piece of data  
  
## Assignment  
  
* Data Analysis Lifecycle  
    * find a real example  
    * how did the project go  
        * did it follow all the stages  
        * what were the issues  
        * were all DA lifecycle steps used  
    * 1,500 words  
* Project Brief  
    * 1,500 words  
  
## Data Projects Ideas  
  
* Operational KPI presentation  
    * SSR / CPB  
