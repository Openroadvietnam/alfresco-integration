# Tích hợp Alfresco và Openroad

## Tổng quan về Alfresco và Openroad
### Alfresco 

[Alfresco](http://www.alfresco.com/) là hệ thống quản lý nội dung doanh nghiệp, hướng tới quản lý nội dung trong một tổ chức. Nội dung Alfresco có thể quản lý bao gồm: Documents, Records, Media, Web Content...

### Openroad

[OpenRoad](http://openroad.vn/) là một phần mềm nguồn mở được phát triển dựa trên [Joinup](https://joinup.ec.europa.eu/), một nền tảng cộng tác và chia sẻ các công nghệ mở nói chung và các ứng dụng nguồn mở nói riêng dành cho khu vực cộng đồng chính phủ Châu Âu.

Xem thêm thông tin: [dự án Openroad](https://github.com/Openroadvietnam/openroad).

## Tại sao phải tích hợp Openroad và Alfresco?

Openroad chưa có một nền tảng quản lý tài liệu cho người dùng. Trong Openroad, một phần không thể thiếu là các thư viện tài liệu điện tử cho phép người dùng có thể truy cập, tìm kiếm và lấy tài liệu tự do hay người dùng có thể chia sẻ tài liệu cho những người dùng khác. 

## Sử dụng Single Sign-On

Thiết lập cơ chế [single sign-on](http://en.wikipedia.org/wiki/Single_sign-on) (sử dụng Central Authentication Server - CAS) cho phép người dùng Openroad sử dụng hệ thống DMS (Alfresco) mà chỉ cần đăng nhập hệ thống duy nhất một lần.

## Mô đun tích hợp Openroad và Alfresco
### Mô đun tích hợp trên Openroad

Openroad sử dụng [mô đun của Drupal](https://drupal.org/project/cas_services) (CAS client) để kết nối với hệ thống sử dụng CAS.

### Mô đun tích hợp trên Alfresco

Alfresco sử dụng [CAS client](https://wiki.jasig.org/display/CAS/CASifying+Zimbra) để kết nối với hệ thống sử dụng CAS.

## Tài liệu

Tài liệu hướng dẫn cài đặt và tích hợp Openroad - Alfresco được đặt trong thư mục [docs](docs).

## Kênh thông tin

* IRC: #openroad on irc.freenode.net
* Mailing list: http://lists.openroad.vn/mailman/listinfo/

## Giấy phép sử dụng

Openroad và module tích hợp do nhóm phát triển Openroad và module giữ quyền tác giả, được phân phối kèm theo giấy phép GNU GPL v2.0. Nguyên văn giấy phép sử dụng có thể được xem trong file [LICENSE](LICENSE).
