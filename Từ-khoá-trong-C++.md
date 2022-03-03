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