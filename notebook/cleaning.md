## Note
- Có thể bỏ cột fee do chỉ có 1 giá trị
- Amenities thay vì chỉ đánh 0-1 có thể tạo cột num_amenities có giá trị là số lượng amenities
- Có 27 amenities trên toàn dataset, xem xét onehot encoding
- Với pets_allowed, tạo cột num_pets_allowed tương ứng với số loại vật nuôi tương ứng: NaN = 0| Cats/Dogs = 1| Cats,Dogs = 2
- Cột has_photos chuyển sang các giá trị 0, 1, 2 theo tình trạng đầy đủ của ảnh: No = 0| Thumbnail = 1| Yes = 2