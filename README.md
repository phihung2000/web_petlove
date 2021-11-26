# Web_PetLove
</br>
Tomcat : 9.0
</br>
version : 1.0
</br>
java version : 1.8
</br>
JDK :1.8.0
</br>
Tải về vào server -> vào tomcat 9 -> vào server.xml -> ở dòng cuối cùng
</br>
Context docBase="webPetLove" path="" reloadable="true" source="org.eclipse.jst.jee.server:webPetLove"/><Context docBase="MovieRecommender" path="/MovieRecommender" reloadable="true" source="org.eclipse.jst.jee.server:MovieRecommender"/
 </br>
sửa path ="" như vậy .
</br>
sau đó khi chạy localhost thì search : http://localhost:8080/shop/homepage  ( đây là trang chủ hiện tất cả các sản phẩm chưa có phân trang vì nó chưa phải trang chính )
</br>
http://localhost:8080/shop/allpet ( trang để cbi cho hệ thống khuyến nghị )
</br>
http://localhost:8080/admin/login ( trang admin) 
</br>
 file webpetlove.txt là file sql tải về đổi tên và chạy thứ tự theo relationship 
 </br>
 ![image](https://user-images.githubusercontent.com/65330451/143565579-994db2fc-fb0a-47e0-8359-83c290d2df55.png)
