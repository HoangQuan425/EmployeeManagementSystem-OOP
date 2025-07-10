# EmployeeManagementSystem-OOP Console Application
## Mô tả:
- Ứng dụng console quản lý nhân viên:
    - quản lý nhân viên xây dựng theo kiến thức OOP, bao gồm các chức năng CRUD, tính lương đơn giản, nhập xuất dùng demo Strategy Pattern.
    - Có phân tách các interface cho đúng nghiệp vụ với ISP trong SOLID
- Mục đích để luyện kiến thức OOP, SOLID, Strategy Pattern, Exception
## Tính năng:
- Thêm, sửa, xóa, cập nhật, tìm kiếm nhân viên 
- tính lương developer và manager (đa hình + trừu tượng)
- sử dụng:
    - Repository pattern
    - Service pattern
    - Strategy pattern
    - Custom Exception
    - ISP
    - xử lý exception handler
## Kiến trúc
    - Entity: chưa Employee, Developer, Manager, Report
    - Repositorys: CRUD data trong List<Employee> 
    - Services: use case logic (Employee service, EmployeeSalaryService, ExportService)
    - Strategies: cho export (CSVExport)
    - Exceptions: Custom exception và exception handler
    - Interface: định nghĩa interface (IEmployeeRepository, IEmployeeService, IExportStrategy, IWork, IReportToManage)
## Môi trường:
    - yêu cầu .NET SDK >=8.0
    - ide visual studio 2022
## Chạy project:
    - git clone https://github.com/HoangQuan425/EmployeeManagementSystem-OOP.git
    - mở solution
    - build and run 
## Author 
    - Hoang Quan
    - Hard work to build basic  