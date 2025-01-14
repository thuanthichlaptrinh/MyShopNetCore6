# MyShopNetCore6

## Entity Framework
  1. Cài đặt thư viện:
    Microsoft.EntityFrameworkCore
    Microsoft.EntityFrameworkCore.SqlServer
    Microsoft.EntityFrameworkCore.Tools
  2. Thêm Db vào entity:
    - Thêm db:
     Scaffold-DbContext "Data Source=localhost\SQLEXPRESS;Initial Catalog=MyShopTest;Integrated Security=True;Encrypt=False" Microsoft.EntityFrameworkCore.SqlServer -        OutputDir Entities
     - Thay đổi db:
     Scaffold-DbContext "Data Source=localhost\SQLEXPRESS;Initial Catalog=MyShopTest;Integrated Security=True;Encrypt=False" Microsoft.EntityFrameworkCore.SqlServer -        OutputDir Entities -f
  3.
