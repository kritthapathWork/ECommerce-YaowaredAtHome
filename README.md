# ECommerce-YaowaredAtHome
ออกแบบและวางโครงสร้างระบบ E-Commerce ขนาดเล็ก - กลาง

## 📄 โครงสร้างระบบ
- HTML
- PHP
- MySQL
- JavaScript
- Bootstrap 5

---

# 📦 Feature ทั้งหมด

---

## 🏰 AUTH PAGE
- เข้าสู่ระบบด้วย Username และรหัสผ่าน
- ระบบตรวจสอบสิทธิ์ Admin และ User

## 🏰 PUBLIC PAGE
## 📦 HOME PAGE
- แสดงรายการสินค้า
- ระบบรองรับการค้นหาตามหมวดหมู่สินค้า

## 🏰 CUSTOMER PAGE
## 📦 CARTS PAGE
#### 🔸 Cart Page
- รองรับการเพิ่ม/ลดจำนวนสินค้า ( Update )
- รองรับการลบรายการสินค้าภายในตะกร้า ( Hard-Delete )

## 📦 SHIPPING PAGE
#### 🔸 Shipping Page
- เพจสำหรับกรอกข้อมูลสำหรับที่อยู่จัดส่งสินค้า
- ระบบรองรับการดึงข้อมูลที่อยู่ของสมาชิกอัตโนมัติ
- ระบบรองรับการแก้ไขที่อยู่สำหรับจัดส่งสินค้าของสมาชิก ( Update )

## 📦 PRODUCTS PAGE
#### 🔸 Product Detail Page ( Read )
- หน้าแสดงรายละเอียดสินค้าแต่ละรายการ

## 📦 ORDERS PAGE
#### 🔸 Order History ( Read )
- แสดงรายการออร์เดอร์ทั้งหมดที่สั่งซื้อ
- ระบบรองรับการยกเลิกรายการออร์เดอร์ ( Cancel )

## 📦 PAYMENTS PAGE
#### 🔸 Payment Proof ( Create )
- ระบบรองรับการส่งหลักฐานการชำระเงิน

## 🏰 ADMIN PAGE
## 📦 DASHBOARD
- ระบบรองรับการเก็บข้อมูล State ที่เกี่ยวข้องกับ E-Commerce เช่น รายการสั่งซื้อทั้งหมด หรือรายการที่รอจัดส่ง

## 📦 ORDERS MANAGEMENT
#### 🔸 Order CRUD ( Read, Hard-Delete )
- จัดการรายการออร์เดอร์
#### 🔸 Order Cancel CRUD ( Read, Hard-Delete )
- จัดการรายการออร์เดอร์ที่ถูกยกเลิก

## 📦 PRODUCTS MANAGEMENT
#### 🔸 Product CRUD ( Read, Create, Update, Hard-Delete )
- จัดการรายการสินค้า
- รองรับการเปลี่ยนแปลงสถานะสินค้า ( Change )
- รองรับการจัดการสต๊อกสินค้าต่อรายการ ( Update )

#### 🔸 Product Category CRUD ( Read, Create, Update, Hard-Delete )
- จัดการประเภทสินค้า

## 📦 USER MANAGEMENT
#### 🔸 User CRUD ( Read, Create, Update, Hard-Delete )
- จัดการข้อมูลสมาชิก
  
## 📦 SHIPPING MANAGEMENT
#### 🔸 Shipping CRUD ( Read, Create, Update, Hart-Delete )
- จัดการกรายการจัดส่ง
- ระบบรองรับการออกรายงาน และดาวโหลด PDF
  
## 📦 REPORT
- ระบบรองรับการออกรายงานยอดระหว่างวัน
- ระบบรองรับการออกรายงานยอดขายรายเดือน
- ระบบรองรับการออกรายงานยอดขายรายปี
