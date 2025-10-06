MSSV: DPM225498
Họ tên: Nguyễn Thị Thu Uyên
Pattern_Composite

Ứng dụng Composite Pattern để mô phỏng cấu trúc cây thư mục (Folder – File).
Mỗi file có dung lượng do người dùng nhập, và mỗi thư mục sẽ tự động tính tổng dung lượng của tất cả các phần tử con (đệ quy).

IComponent: interface chung cho cả File và Folder.

FileLeaf: lớp con biểu diễn tệp tin, chứa dung lượng.

FolderComposite: lớp thư mục, có danh sách phần tử con và tính tổng dung lượng.

Chương trình cho phép nhập dung lượng file, sau đó in ra cấu trúc cây + dung lượng từng thư mục.
