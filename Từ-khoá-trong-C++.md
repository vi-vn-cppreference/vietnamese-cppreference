# Từ khoá trong C++
### [Bài gốc](https://en.cppreference.com/w/cpp/keyword)

Dưới đây là danh sách các từ khoá đặc biệt trong ngôn ngữ C++. Bởi vì chúng đã được sử dụng bởi ngôn ngữ, các từ khoá này không thể được tái định nghĩa (re-definition) hoặc ghi đè (overloading).

|          A - C           |          D - P           |          R - Z           |
|--------------------------|--------------------------|--------------------------|
| alignas (từ C++ 11)      | decltype (từ C++ 11)     | reflexpr (reflection TS) |
| alignof (từ C++ 11)      | default (1)              | register (2)             |
| and                      | delete (1)               | reinterpret_cast         |
| and_eq                   | do                       | requires (từ C++ 20)     |
| asm                      | double                   | return                   |
| atomic_cancel (TM TS)    | dynamic_cast             | short                    |
| atomic_commit (TM TS)    | else                     | signed                   |
| atomic_noexcept (TM TS)  | enum                     | sizeof (1)               |
| auto (1)                 | explicit                 | static                   |
| bitand                   | export (1) (3)           | static_assert (từ C++ 11)|
| bitor                    | extern (1)               | static_cast              |
| bool                     | false                    | struct (1)               |
| break                    | float                    | switch                   |
| case                     | for                      | synchronized (TM TS)     |
| catch                    | friend                   | template                 |
| char                     | goto                     | this                     |
| char8_t (từ C++ 20)      | if                       | thread_local (từ C++ 11) |
| char16_t (từ C++ 11)     | inline (1)               | throw                    |
| char32_t (từ C++ 11)     | int                      | true                     |
| class (1)                | long                     | try                      |
| compl                    | mutable (1)              | typedef                  |
| concept (từ C++ 20)      | namespace                | typeid                   |
| const                    | new                      | typename                 |
| consteval (từ C++ 20)    | noexcept (từ C++ 11)     | union                    |
| constexpr (từ C++ 11)    | not                      | unsigned                 |
| constinit (từ C++ 20)    | not_eq                   | using (1)                |
| const_cast               | nullptr (từ C++ 11)      | virtual                  |
| continue                 | operator                 | void                     |
| co_await (từ C++ 20)     | or                       | volatile                 |
| co_return (từ C++ 20)    | or_eq                    | wchar_t                  |
| co_yield (từ C++ 20)     | private                  | while                    |
|                          | protected                | xor                      |
|                          | public                   | xor_eq                   |

Chú thích:
- (1) - Nghĩa của từ khoá được thay đổi hoặc một nghĩa mới đã được thêm trong phiên bản C++ 11.
- (2) - Nghĩa của từ khoá được thay đổi trong phiên bản C++ 17.
- (3) - Nghĩa của từ khoá được thay đổi trong phiên bản C++ 20.

Chú ý rằng những từ khoá: and, bitor, or, xor, compl, bitand, and_eq, or_eq, xor_eq, not, và not_eq (cùng với các ký tự <:, :>, %:, và %:%:) cung cấp một cách tương tự để biểu diễn ký hiệu (token) tiêu chuẩn.

Bên cạnh những từ khoá trên, các định danh (identifier) với ý nghĩa đặc biệt, có thể được sử dụng như tên của các đối tượng hoặc hàm, nhưng chúng có ý nghĩa đặc biệt trong các ngữ cảnh nhất định.
- final (C++ 11)
- override (C++ 11)
- transaction_safe (TM TS)
- transaction_safe_dynamic (TM TS)
- import (C++ 20)
- module (C++ 20) 

Thêm vào đó, tất cả các định danh chứa hai dấu gạch dưới __ trong bất kỳ vị trí nào và mỗi định danh bắt đầu với một dấu gạch dưới, sau đó là một chữ cái in hoa thường là các từ đặc biệt và tất cả các định danh bắt đầu với một dấu gạch dưới _ được dành để dùng như tên trong ký hiệu tên (namespace) toàn cục. Xem phần [định danh](https://en.cppreference.com/w/cpp/language/identifiers) để biết thêm chi tiết.

Ký hiệu tên std được dùng để chứa các tên của thư viện C++ tiêu chuẩn. Xem phần [Ký hiệu tên std mở rộng](https://en.cppreference.com/w/cpp/language/extending_std) để biết thêm về quy tắc thêm tên vào std.

Từ khoá posix được dành cho một ký hiệu tên bậc cao trong tương lai. Hành vi sẽ không được định nghĩa nếu một chương trình khai báo hoặc định nghĩa bất kỳ thứ gì trong ký hiệu tên đó.

Các ký hiệu dưới đây được nhận dạng bởi bộ tiền xử lý (preprocessor) khi ở trong ngữ cảnh của một chỉ thì của bộ tiền xử lý:

|       |        |         |                                 |                 |
|-------|--------|---------|---------------------------------|-----------------|
| if    | ifdef  | include | defined                         | export (C++ 20) |
| elif  | ifndef | line    | __has_include (từ C++ 17)       | import (C++ 20) |
| else  | define | error   | __has_cpp_attribute (từ C++ 20) | module (C++ 20) |
| endif | undef  | pragma  |                                 |                 |

Các ký hiệu dưới đây được nhận dạng bởi bộ tiền xử lý (preprocessor) khi ở ngoài ngữ cảnh của một chỉ thì của bộ tiền xử lý:
_Pragma (từ C++ 11)

Xem thêm [Tài liệu ngôn ngữ C](https://en.cppreference.com/w/c/keyword) cho **Từ khoá trong ngôn ngữ C**