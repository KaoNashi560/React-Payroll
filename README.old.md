# React-Payroll
## Tables
- users
  - id
  - role
  - username
  - password
- admins
  - id
  - name
  - user_id
- employees
  - id
  - first_name
  - middle_name
  - last_name
  - position_id
  - deduction_id
  - user_id
qr_codes
  - id
  - code
  - date
  - employee_id
- positions
  - id
  - name
  - basic_salary_per_hour
  - honorarium_amount
- schedules
  - id
  - start_time
  - break_start_time
  - break_end_time
  - end_time
  - employee_id
- attendances
  - id
  - first_time_in
  - first_time_out
  - second_time_in
  - second_time_out
  - employee_id
- deductions
  - id
  - for
  - description
  - amount
  - employee_id
- overtime
  - id
  - reason
  - attendance_id
- pay_slips
  - id
  - start_date
  - end_date
  - net_amount
  - employee_id
  - prepared_by_id(admin_id)


Pages
- Public
  - login page
- Employee
  - index page
    - qr code for time in or time out
  - attendance page
    - weekly lates, undertime, and overtime data
    - list of past attendance and hour consumptions
  - position information page
    - position name
    - basic salary
  - duductions page
    - list of deductions
  - payslips page
    - list of payslips received
  - employee profile page
    - edit image, name, profile description, contact_number, email, address, usrname, and password feature
    - activity logs for profile modifications
  - message
    - message co-employee
    - message admin
- Amdin
  - employee list page
    - send payslip to all employee in message feature
    - employee creation page
    - employee configuration, edit and delete feature (editing position or adding deductions)
    - list of employees
  - attendance list page
    - today's late, undertime, and overtime date
    - list of attendance
    - specific employee attendace data
  - positions page
    - positions employee count data
    - position creation feature
    - position modification or edit feature
    - position list
  reports
    - overall salary report
    - 


