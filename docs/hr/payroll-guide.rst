==================
Payroll Management
==================

Processing payroll of employees can be cumbersome and a time-consuming activity taking into account the financial and legal implications. Changes in tax, employee regulations, and legal compliances can make payroll processing a painfully complex task. Being one of the most important tasks carried out in an organisation, it is significant to ensure that there are no challenges in the process.


Challenges of Processing Payroll
================================

As your organization grows and employees start to step in and out of your team, HR management can become difficult. Some common challenges of processing payroll are

- Compliance
- Accuracy
- Tax Regulations
- Employee Data management
- Security
- Managing changes based on evolving conditions (for example, the amount of Income Tax to be deducted changing across financial years)


Sigma's 5 Step Payroll
========================

Step 1: Define Salary Components
--------------------------------

The salaries that are offered to employees involve various components ranging from basic, House Allowance (HA), Personal Income Tax (PT), and so on. A salary component either be an **Earning** or a **Deduction** based on how it is defined. You can add the amount directly or it can be an amount calculated on the basis of base salary or a particular rate or based on a formula involving the other components as well.

You can create salary components and define whether the component is an Earning or a Deduction component. There are certain checkboxes that you can check depending on the component type. Select the company and a default ledger account. Now, these salary components can be based on a particular formula or it can be a fixed amount.

Step 2: Create a Salary Structure
---------------------------------

Once you have created all the salary components, you can define a salary structure. You can also define whether the salary is based on timesheets. You can add the earnings and deductions as per your choice and the mode of payment.

Salary Structure represents how salaries are created in SIGMA based on earnings and deductions. In simple words, it is the breakup of the salary offered to your employees. Creation of salary structures in SIGMA requires you to first create Salary Components.

The current Salary Structure is such that each Employee Grade has a corresponding Salary Structure. So unless there is a change of earnings or deductions, the salary structures remain the same.

.. image::  ../_static/images/hr/salary_structure.png
	:width: 600
	:alt: Salary Structure


Step 3. Assign the Salary Structure
-----------------------------------

Once the salary structures have been created, you need to assign salary structures to employees. If you miss this step, then you will not be able to generate salary slips. During assignment, you assign a Salary Structure to an employee. The system will use the assigned salary structure to generate the employee's salary slips. 

.. image::  ../_static/images/hr/salary_structure_assignment.png
	:width: 600
	:alt: Salary Structure
    
.. note::

	- You must ensure that you set the value of **Default base pay** since all other earnings have the value of **Default base pay** in their formula
	- Whenever an employee changes a grade, make a new Salary Structure Assignment for the employee assiging the current salary structure associated with the employee's new grade


Step 4. Create a Payroll Entry & Salary Slips
---------------------------------------------

Once all of the above steps are done, you need to create a payroll entry. Once you have selected the payroll date, frequency and added the payment account, you can filter employees on the basis on department, designation and branch. If you do not wish to do so then you can directly click on 'Get employees'. On doing so, a list of all the employees will populate in the Employee Details section. You can then proceed by clicking on "Create Salary Slips" and all the salary slips will be generated in draft.

.. image::  ../_static/images/hr/payroll_entry.png
	:width: 600
	:alt: Payroll Entry

You can verify the draft salary slips and then submit them via the payroll entry. On submitting the salary slips, an accrual journal entry will be created. This means we are booking the salary expenses in the system and not paying them.

.. image::  ../_static/images/hr/confirm_salary_slips.png
	:width: 600
	:alt: Confirm Salary Slips


Step 5. Bank Entry
------------------

Once you have booked the accrued salary slips, as a last step you need to make a Bank Entry. With this last step, your payroll process is completed, but this does not mean the salaries are transferred in the bank. That minor step has to be done manually.

.. image::  ../_static/images/hr/payroll_bank_entry.png
	:width: 600
	:alt: Payroll Bank Entry
