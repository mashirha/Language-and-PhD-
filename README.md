	<!DOCTYPE html>
	<html lang="ar" dir="rtl">
	<head>
	<meta charset="UTF-8">
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
	<title>البحث المتقدم - فهرس مكتبات جامعة صنعاء</title>
	<link rel="stylesheet" href="css/style.css">
	</head>
	<body>
	
	<header class="main-header">
	<div class="container">
	    <div class="logo">
	        
	        <h1>فهرس مكتبات جامعة صنعاء الموحد</h1>
	    </div>
	    <nav class="main-nav">
	        <ul>
	            <li><a href="index.html">الشاشة الرئيسية</a></li>
	            <li><a href="add-book.html">إضافة كتب جديدة</a></li>
	            <li><a href="manage-catalogs.html">إدارة الفهارس</a></li>
	            <li><a href="reports.html">التقارير والإحصائيات</a></li>
	        </ul>
	    </nav>
	</div>
	</header>
	
	<main class="content-section">
	<div class="container">
	    <h2>البحث المتقدم عن الكتب</h2>
	    <form class="search-form" id="advancedSearchForm">
	        <div class="form-group">
	            <label for="searchText">نص البحث:</label>
	            <input type="text" id="searchText" name="searchText" placeholder="العنوان، المؤلف، الكلمات المفتاحية...">
	        </div>
	
	        <div class="form-group">
	            <label for="author">المؤلف:</label>
	            <input type="text" id="author" name="author" placeholder="اسم المؤلف">
	        </div>
	
	        <div class="form-group">
	            <label for="genre">النوع:</label>
	            <select id="genre" name="genre">
	                <option value="">جميع الأنواع</option>
	                <option value="science">علمي</option>
	                <option value="literature">أدب</option>
	                <option value="history">تاريخ</option>
	                <option value="engineering">هندسة</option>
	                <option value="law">قانون</option>
	                </select>
	        </div>
	
	        <div class="form-group">
	            <label for="publicationYear">سنة النشر:</label>
	            <input type="number" id="publicationYear" name="publicationYear" min="1900" max="2025" placeholder="مثال: 2020">
	        </div>
	
	        <button type="submit" class="btn-primary">بحث</button>
	    </form>
	
	    <div class="search-results" id="searchResults">
	        <h3>نتائج البحث:</h3>
	        <p>لا توجد نتائج لعرضها حالياً. يرجى إجراء بحث.</p>
	    </div>
	
	     <div class="upload-reference-section">
	        <h3>هل لديك مراجع تود إضافتها؟</h3>
	        <p>ساهم في إثراء الفهرس برفع كتب أو مراجع بصيغة PDF.</p>
	        <button class="btn-secondary" onclick="location.href='upload-reference.html'">رفع مرجع جديد</button>
	    </div>
	
	</div>
	</main>
	
	<footer class="main-footer">
	<div class="container">
	    <p>&copy; 2025 جامعة صنعاء - جميع الحقوق محفوظة.</p>
	</div>
	</footer>
	
	<script src="js/script.js"></script>
	</body>
	</html>
	
