  
<!-- ![blockchain](https://upload-images.jianshu.io/upload_images/6860761-fd2f51090a890873.jpg?imageMogr2/auto-orient/strip%7CimageView2/2/w/550/format/webp '区块链')
 -->

 
[demo](https://yzty.github.io/dome.github.io/src/code/CSS开关按钮.html 'demo') 连接效果
 

## 代码
  
代码块：

```html 
<!DOCTYPE html>
<html lang="en" manifest="cache.manifest">
	<head>
		<meta charset="utf-8" />
		<meta name="viewport" content="width=device-width, initial-scale=1">
		<title></title>
		<style type="text/css">
			.cmn-toggle {
				position: absolute;
				margin-left: -9999px;
				visibility: hidden;
			}

			.cmn-toggle+label {
				display: block;
				position: relative;
				cursor: pointer;
				outline: none;
				user-select: none;
			}
		</style>
		<style type="text/css">
			input.cmn-toggle-round+label {
				padding: 2px;
				width: 120px;
				height: 60px;
				background-color: #dddddd;
				border-radius: 60px;
			}

			input.cmn-toggle-round+label:before,
			input.cmn-toggle-round+label:after {
				display: block;
				position: absolute;
				top: 1px;
				left: 1px;
				bottom: 1px;
				content: "";
			}

			input.cmn-toggle-round+label:before {
				right: 1px;
				background-color: #f1f1f1;
				border-radius: 60px;
				transition: background 0.4s;
			}

			input.cmn-toggle-round+label:after {
				width: 58px;
				background-color: #fff;
				border-radius: 100%;
				box-shadow: 0 2px 5px rgba(0, 0, 0, 0.3);
				transition: margin 0.4s;
			}

			input.cmn-toggle-round:checked+label:before {
				background-color: #8ce196;
			}

			input.cmn-toggle-round:checked+label:after {
				margin-left: 60px;
			}
		</style>
		<style type="text/css">
			input.cmn-toggle-round-flat+label {
				padding: 2px;
				width: 120px;
				height: 60px;
				background-color: #dddddd;
				border-radius: 60px;
				transition: background 0.4s;
			}

			input.cmn-toggle-round-flat+label:before,
			input.cmn-toggle-round-flat+label:after {
				display: block;
				position: absolute;
				content: "";
			}

			input.cmn-toggle-round-flat+label:before {
				top: 2px;
				left: 2px;
				bottom: 2px;
				right: 2px;
				background-color: #fff;
				border-radius: 60px;
				transition: background 0.4s;
			}

			input.cmn-toggle-round-flat+label:after {
				top: 4px;
				left: 4px;
				bottom: 4px;
				width: 52px;
				background-color: #dddddd;
				border-radius: 52px;
				transition: margin 0.4s, background 0.4s;
			}

			input.cmn-toggle-round-flat:checked+label {
				background-color: #8ce196;
			}

			input.cmn-toggle-round-flat:checked+label:after {
				margin-left: 64px;
				background-color: #8ce196;
			}
		</style>
	</head>
	<body>
		<div class="switch">
			<input id="cmn-toggle-1" class="cmn-toggle cmn-toggle-round" type="checkbox">
			<label for="cmn-toggle-1"></label>
		</div>

		<div class="switch">
			<input id="cmn-toggle-4" class="cmn-toggle cmn-toggle-round-flat" type="checkbox">
			<label for="cmn-toggle-4"></label>
		</div>

		<div class="switch">
			<input id="cmn-toggle-7" class="cmn-toggle cmn-toggle-yes-no" type="checkbox">
			<label for="cmn-toggle-7" data-on="Yes" data-off="No"></label>
		</div>



	</body>

	<script type="text/javascript">
		const isType = type => target => `[object ${type}]` === Object.prototype.toString.call(target)
		const isArray = isType('Object')
		console.log(isArray([]))
		var a = '2019/6/4'
		console.log(a.replace(/\//g, "-"))
	</script>
</html>


```

 