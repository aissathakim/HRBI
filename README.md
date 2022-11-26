# HRBI
ldv

01_Action_Entity_To_Action_Entity
01_Action_Entity_To_Range
01_Action_Entity_To_Effective_Date
        01_Action_Entity_To_Action_Category
        01_Action_Entity_To_Action_Employee_Status
        01_Action_Entity_To_Action_Reason
        01_Action_Entity_To_Action_Type


02_Bonus_Entity_To_Bonus_Entity
02_Bonus_Entity_To_Range
02_Bonus_Entity_To_Effective_Date
        02_Bonus_Entity_To_Bonus_Currency
        02_Bonus_Entity_To_Bonus_Reason
        02_Bonus_Entity_To_Bonus_Type


03_Cost_Center_Fnc_Area_To_Cost_Center

        09_Employee_Entity_To_Action_Entity
        09_Employee_Entity_To_Range
        09_Employee_Entity_To_Effective_Date
        
        14_Job_Entity_To_Range
        14_Job_Entity_To_Effective_Date
        
        21_Salary_Entity_To_Action_Entity
        21_Salary_Entity_To_Range
        21_Salary_Entity_To_Effective_Date

        17_Position_Entity_To_Range
        17_Position_Entity_To_Effective_Date

ldt

        01_Action_Entity
        02_Bonus_Entity
        03_Cost_Center_Fnc_Area
        04_Employee_Ad
        05_Employee_Champion
        06_Employee_Division
        07_Employee_Division_Group
        08_Employee_Emp_Aux_Man_Ref
        09_Employee_Entity
        10_Employee_Groups
        11_Employee_HSA
        12_Exchange_Rates_Ref
        13_Job
        14_Job_Entity
        15_Locations_Hrmny_Ref
        16_Locations_Ref
        17_Position_Entity
        18_Ref_Default_Values
        19_Ref_Values
        20_Ref_Values_Mappings
        21_Salary_Entity


Action_Entity

        Action_Entity_To_Ref_Values_Mappings
        Action_Entity_To_Ref_Values
                Action_Entity_To_Action_Category
                Action_Entity_To_Action_Employee_Status
                Action_Entity_To_Action_Reason
                Action_Entity_To_Action_Type

        Action_Entity_To_Range (ldv01)
        Action_Entity_To_Effective_Date (ldv01)
                EMPLOYEE_ACTION_START_DT
                EMPLOYEE_ACTION_END_DT

Bonus_Entity

        Bonus_Entity_To_Ref_Values_Mappings
        Bonus_Entity_To_Ref_Values    
                Bonus_Entity_To_Bonus_Currency
                Bonus_Entity_To_Bonus_Reason
                Bonus_Entity_To_Bonus_Type
        
        Bonus_Entity_To_Range (ldv02)
        Bonus_Entity_To_Effective_Date (ldv02)
                BONUS_START_DT
                BONUS_END_DT
        
Employee_Entity

        Employee_Entity_To_Ref_Values_Mappings
        Employee_Entity_To_Ref_Values
                Employee_Entity_To_Employee_I9_Status
                Employee_Entity_To_Employee_Aboriginal
                Employee_Entity_To_Employee_Disability
                Employee_Entity_To_Employee_Ethnicity
                Employee_Entity_To_Employee_Gender
                Employee_Entity_To_Employee_Marital_Status
                Employee_Entity_To_Employee_Military_Status
                Employee_Entity_To_Employee_Status
                Employee_Entity_To_Employee_Suffix
                Employee_Entity_To_Position_Collar
                Employee_Entity_To_Position_Full_Part_Time
                Employee_Entity_To_Position_Grade
                Employee_Entity_To_Position_Group
                Employee_Entity_To_Position_Subgroup
                Employee_Entity_To_Position_Type
                Employee_Entity_To_Position_Union
                Employee_Entity_To_Employee_Language
                       
        Employee_Entity_To_Range (ldv09)
        Employee_Entity_To_Effective_Date (ldv09)
                COST_CENTER_EFFECTIVE_DT
                LOCATION_EFFECTIVE_DT
                ORG_UNIT_EFFECTIVE_DT
                PAYROLL_EFFECTIVE_DT
                EMPLOYEE_EFFECTIVE_DT
                
        Employee_Entity_To_Cost_Center
        Employee_Entity_To_Location
        Employee_Entity_To_Org_Unit
        Employee_Entity_To_Payroll

Job_Entity

        Job_Entity_To_Ref_Values 
        Job_Entity_To_Ref_Values_Mappings 
                Job_Entity_To_Occupation_Collar
                Job_Entity_To_Occupation_Full_Part_Time
                Job_Entity_To_Occupation_Grade
                Job_Entity_To_Occupation_Group
                Job_Entity_To_Occupation_Subgroup
                Job_Entity_To_Occupation_Type
                Job_Entity_To_Occupation_Union

        Job_Entity_To_Range (ldv14)
        Job_Entity_To_Effective_Date (ldv14)
                COST_CENTER_EFFECTIVE_DT
                LOCATION_EFFECTIVE_DT
                ORG_UNIT_EFFECTIVE_DT
                PAYROLL_EFFECTIVE_DT
                EMPLOYEE_MANAGER_EFFECTIVE_DT
        
        Job_Entity_To_Cost_Center
        Job_Entity_To_Location
        Job_Entity_To_Org_Unit
        Job_Entity_To_Payroll
        
Position_Entity        

        Position_Entity_To_Ref_Values_Mappings
        Position_Entity_To_Ref_Values        
                Position_Entity_To_Position_Collar
                Position_Entity_To_Position_Full_Part_Time
                Position_Entity_To_Position_Grade
                Position_Entity_To_Position_Group
                Position_Entity_To_Position_Subgroup
                Position_Entity_To_Position_Type
                Position_Entity_To_Position_Union
                Position_Entity_To_Position_Pay_Frequency
                
        Position_Entity_To_Range (ldv17)
        Position_Entity_To_Effective_Date (ldv17)
                COST_CENTER_EFFECTIVE_DT
                LOCATION_EFFECTIVE_DT
                ORG_UNIT_EFFECTIVE_DT
                PAYROLL_EFFECTIVE_DT
                EMPLOYEE_EFFECTIVE_DT
                
        Position_Entity_To_Cost_Center
        Position_Entity_To_Location
        Position_Entity_To_Org_Unit
        Position_Entity_To_Payroll
        
Salary_Entity

        Salary_Entity_To_Ref_Values_Mappings
        Salary_Entity_To_Ref_Values
                Salary_Entity_To_Compensation_Type
                Salary_Entity_To_Currency
                Salary_Entity_To_Salary_Level
                Salary_Entity_To_Pay_Scale_Group]
                Salary_Entity_To_Salary_Reason
                
        Salary_Entity_To_Range (ldv21)
        Salary_Entity_To_Effective_Date (ldv21)
                SALARY_START_DT
                SALARY_END_DT
                TARGET_BONUS_START_DT
                TARGET_BONUS_END_DT
                
Exchange_Rates_Ref

        Exchange_Rates_Ref_To_Ref_Values_Mappings
        Exchange_Rates_Ref_To_Ref_Values
                Exchange_Rates_Ref_To_Currency

Ref_Values_Mappings

        Ref_Values_Mappings_To_Ref_Values_Mappings
        Ref_Values_Mappings_To_Ref_Values
        
Ref_Values

        Ref_Values_To_Ref_Values
        
Cost_Center_Fnc_Area   

        Cost_Center_Fnc_Area_To_Cost_Center
        
Locations_Ref

        Locations_Ref_To_Location
        Locations_Ref_To_Location_Type
        
Employee_Division_Group

        Employee_Division_Group_To_Location_Type
        

