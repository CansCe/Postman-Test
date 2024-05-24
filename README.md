# Postman

## API được chọn 
API được chọn là HTTP poke api, api cung cấp hình ảnh mèo

## Phân tích API
### API: https://pokeapi.co/api/v2/pokemon/pikachu
### Phương thức: GET

## Các trường hợp kiểm thử:
### TH1: truy vấn hợp lệ
#### GET: (https://pokeapi.co/api/v2/pokemon/pikachu)
#### Kết quả: Mã trạng thái 200 và ảnh tương ứng với id
![image](https://github.com/CansCe/Postman-Test/assets/93910580/aa9c8f54-e95d-4159-9e49-6bbd336d8dde)


### TH2: truy vấn không hợp lệ
#### GET: (https://pokeapi.co/api/v2/pokemon/pikachuu)
#### Kết quả: Mã trạng thái 404 và thông báo Not Found
![image](https://github.com/CansCe/Postman-Test/assets/93910580/43ee7141-2571-47f9-86a7-676d9c50603a)


### POST, PUT, DELETE
#### Kết quả: Failed vì không được cấp phép
![image](https://github.com/CansCe/Postman-Test/assets/93910580/cab8ea05-8bef-489a-8a49-b2e03d84d020)

## Mục Tiêu Kiểm Thử:
- Xác định và xác thực các phản hồi của Poke API dựa trên các truy vấn khác nhau.

## Phạm Vi Kiểm Thử:
- Các điểm cuối liên quan đến việc lấy dữ liệu.

## Kết Quả Kiểm Thử:
- Tất cả các trường hợp kiểm thử được thực hiện và kết quả phù hợp với mong đợi.
- API hoạt động đúng với tên hợp lệ và xử lý các lỗi một cách thích hợp khi cung cấp dữ liệu không hợp lệ.

## Khuyến Nghị:
- API hoạt động tốt và xử lý các lỗi đúng cách.
