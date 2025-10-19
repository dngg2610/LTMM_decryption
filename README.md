🔓 RC4 Decryption in C

Chương trình này thực hiện giải mã (decryption) cho dữ liệu đã được mã hóa bằng RC4.
RC4 sử dụng cùng khóa K và vector S để tạo lại dòng khóa, sau đó XOR với ciphertext để khôi phục plaintext gốc.

⚙️ Cách biên dịch và chạy
Mở terminal trong thư mục chứa mã nguồn (thư mục có file main.c của phần decrypt).
Biên dịch toàn bộ chương trình:
gcc *.c -o rc4_decrypt.exe

Chạy chương trình:
./rc4_decrypt


🧠 Dữ liệu mẫu để nhập



Nếu ciphertext được tạo từ phần Encryption trước đó, hãy nhập lại đúng cùng thông số:

Nhap do dai cua vector S: 256
Nhap do dai cua khoa K: 5
Nhap gia tri cua K:
1 2 3 4 5
Nhap chieu dai chuoi Ciphertext: 44
Nhap Ciphertext: Ä ½ Ò ­ ¹ ª ...   (các ký tự mã hóa từ bước mã hóa trước đó)


📤 Kết quả mẫu (ví dụ)



Chương trình sẽ hiển thị:

Khoi tao gia tri ban dau cua S !
0 1 2 3 ... 255
Vector khoi tao T !
1 2 3 4 5 ...
Vector hoan vi S !
...
Dong khoa la: 57 12 203 99 ...
Plaintext la: H a n o i   U n i v e r s i t y   o f   S c i e n c e   a n d   T e c h n o l o g y


Như vậy -> Kết quả cuối cùng chính là chuỗi plaintext ban đầu, cho thấy code đã chạy chính xác

Hanoi University of Science and Technology
