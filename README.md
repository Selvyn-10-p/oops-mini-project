// -------------------------------
// CLASS 1 : EMPLOYEE
// -------------------------------
class Employee {
    private int empId;
    private String name;
    private double basicSalary;
    private int attendanceDays;
    private int leaveDays;
    private int overtimeHours;

    public Employee(int empId, String name, double basicSalary) {
        this.empId = empId;
        this.name = name;
        this.basicSalary = basicSalary;
    }

    public void setMonthlyData(int attendanceDays, int leaveDays, int overtimeHours) {
        this.attendanceDays = attendanceDays;
        this.leaveDays = leaveDays;
        this.overtimeHours = overtimeHours;
    }

    public int getEmpId() { return empId; }
    public String getName() { return name; }
    public double getBasicSalary() { return basicSalary; }
    public int getAttendanceDays() { return attendanceDays; }
    public int getLeaveDays() { return leaveDays; }
    public int getOvertimeHours() { return overtimeHours; }
}
