BR1: improving the statistical quality of clinical trial reporting to meet the needs of external audits
BR2: increasing the throughput of trial analyses to meet higher demand during peak periods

the names of all patients (SR3.1.1) and doctors (SR3.1.2) involved in the trial
the name of the doctor for a particular patient (SR3.1.3)
a group of patients being administered by a particular doctor (SR3.2.1).


UR1.1 (from BR1): add support for statistical measures in generated trial reports as required by revised auditing standards (standard deviation, …)
UR1.2 (from BR1): add support for producing textual representations of statistics in trial reports as required by revised auditing standards
UR2.1 (from BR2): ability to have an individual trial report processed and generated in under 30 seconds (if we assume it usually takes longer than that)


Functional requirements focus on functions and features of a solution. For our software, building on our user requirements, e.g.:
SR1.1.1 (from UR1.1): add standard deviation to data model and include a graph visualisation view
SR1.2.1 (from UR1.2): add a new view to generate a textual representation of statistics, which is invoked by an optional command line argument
Non-functional requirements focus on how the behaviour of a solution is expressed or constrained, e.g. performance, security, usability, or portability. These are also known as quality of service requirements. For our project, e.g.:
SR2.1.1 (from UR2.1): generate graphical statistics report on clinical workstation configuration in under 30 seconds


MVC: Model View Controller