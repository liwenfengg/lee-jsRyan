# javascriptRyan
#####冒泡排序
```javascript
	<script>
	// 一组数据，从小到大排列
	var array = [9,5,22,3,100]
	// 控制比较轮数，若不加此循环，则输出[5, 9, 3, 22, 100]，
	for (var j = 0; j < array.length-1; j++) {
		// for循环
		for (var i = 0; i < array.length-1-j; i++) {
			// 比较一次，要多次--for循环
			if (array[i]>array[i+1]) {
				var temp = array[i];
				array[i] = array[i+1];
				array[i+1] = temp;
			}
		}
	}
	console.log(array);
	</script>
```javascript