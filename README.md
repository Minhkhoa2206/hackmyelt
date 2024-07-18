# HACK BÀI TẬP MYELT 2024
# CODE TẠI ĐÂY: 
// Tìm tất cả các nút có lớp 'show-answer-button'
const buttons = document.querySelectorAll('.show-answer-button');
// Duyệt qua tất cả các nút và hiển thị chúng
buttons.forEach(button => {
  // Bỏ thuộc tính 'ng-hide' 
  button.classList.remove('ng-hide');
  
  // Bỏ 'disabled' để kích hoạt nút
  button.removeAttribute('disabled');
});

