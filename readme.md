df.na.drop(how="any", thresh = 1).show() dùng để xóa các dòng bị null nhưng có 1 dòng có dữ liệu. tường tự như 2 thì xóa các dòng nhưng để lại các dòng có 2 cột dữ liệu còn trong dòng
df.na.drop(how="any", subset = ["ten cot"]).show()   xóa các dòng mà trong ten_cot có null. các cột còn lại có null k sao
df.na.fill("MISSING VALUE").show()   thay các phần tử null bằng MISSING VALUE
df.na.fill("MISSING VALUE" ['ten_cot', 'ten_cot']).show()   thay các phần tử null ở các cột đã chọn bằng MISSING VALUE
