<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>🛒RUFON_STORE</title>
</head>
<body>
    <div class="container-lg px-3 my-5 markdown-body">
      
        <header>
            <h1><a href="https://angelcb07.github.io/RUFON_STORE/">RUFON_STORE</a></h1>
            <p>¡Encuentra tus productos aquí!</p>
            <form>
                <input type="text" placeholder="Buscar producto..." />
                <button>Buscar</button>
            </form>
        </header>

        <hr />

        <main>
            <h2>Productos</h2>
                <tr>
                    <td>
                        <a href="https://infotecshop.pe/products/laptop-hp-250-g10-core-i5-16gb-512gb-ssd-15-7?variant=46985556197545">
                            <img src="https://infotecshop.pe" width="200" />
                        </a>
                        <p><b>Laptop Hp 250 G10 Core I5 16GB 512GB SSD 15.6”</b></p>
                        <p>Precio: S/2579.00</p>
                        <p>ENVIO TODO EL PERU</p>
                    </td>
                    <td>
                        <a href="https://infotecshop.pe/products/laptop-lenovo-v15-g5-irl-core-i3-8gb-256gb-ssd-15-6?variant=46936654348457">
                            <img src="https://infotecshop.pe/cdn/shop/files/LENOVOV15G5IRLINTELI3-1315U_jpg.jpg?v=1774617603" width="200" />
                        </a>
                        <p><b>Laptop Lenovo V15 G5 IRL Core I3 8GB 256GB SSD 15.6”</b></p>
                        <p>Precio: S/1619.00</p>
                        <p>ENVIO TODO EL PERU</p>
                    </td>
                </tr>
                <tr>
                    <td>
                        <a href="https://infotecshop.pe/products/laptop-hp-victus-15-fb3018la-ryzen-7-8gb-512gb-ssd-15-6?variant=46935343562921">
                            <img src="https://infotecshop.pe/cdn/shop/files/HPVICTUS15-FB3018LA_3__jpg.jpg?v=1774549362" width="200" />
                        </a>
                        <p><b>Laptop Hp Victus 15-FB3018LA Ryzen 7 8GB 512GB SSD 15.6”</b></p>
                        <p>Precio: S/3419.00</p>
                        <p>ENVIO TODO EL PERU</p>
                    </td>
                    <td>
                        <a href="https://infotecshop.pe/products/laptop-lenovo-essential-loq-15irx11-core-i5-16gb-512gb-ssd-15-6?variant=46935346315433">
                            <img src="https://infotecshop.pe/cdn/shop/files/LENOVOASSENTIALLOQ15IRX11I5-13450HX_jpg.jpg?v=1774549764" width="200"/>
                        </a>
                        <p><b>Laptop Lenovo Essential LOQ 15IRX11 Core i5 16GB 512GB SSD 15.6</b></p>
                        <p>Precio: S/4,489.00</p>
                        <p>ENVIO TODO EL PERU</p>
                    </td>
                </tr>
                <tr>
                    <td>
                        <a href="https://infotecshop.pe/products/laptop-lenovo-loq-15irx9-core-i7-16gb-512gb-ssd-15-6?variant=46019287023785">
                            <img src="https://infotecshop.pe/cdn/shop/files/LenovoLOQ15IRX9I7.jpg?v=1751478707" width="200"/>
                        </a>
                        <p><b>Laptop Lenovo LOQ 15IRX9 Core I7 16GB 512GB SSD 15.6”</b></p>
                        <p>Precio: S/5,159.00</p>
                        <p>ENVIO TODO EL PERU</p>
                    </td>
                    <td>
                        <a href="https://infotecshop.pe/products/laptop-lenovo-loq-15ahp10-ryzen-7-250-16gb-1tb-ssd-15-6?_pos=51&amp;_fid=cca587cbe&amp;_ss=c?variant=46935352017065">
                            <img src="https://infotecshop.pe/cdn/shop/files/LENOVO_LOQ_15AHP10_3__jpg.jpg?v=1774550383" width="200"/>
                        </a>
                        <p><b>Laptop Lenovo LOQ 15AHP10 Ryzen 7-250 16GB 1TB SSD 15.6</b></p>
                        <p>Precio: S/5,949.00</p>
                        <p>ENVIO TODO EL PERU</p>
                    </td>
                </tr>
            </table>
        </main>

        <footer>
            <hr>
            <p>© 2026 RUFON_STORE - Venta de Laptops</p>
        </footer>
    </div>
<!-- Code injected by live-server -->
<script>
	// <![CDATA[  <-- For SVG support
	if ('WebSocket' in window) {
		(function () {
			function refreshCSS() {
				var sheets = [].slice.call(document.getElementsByTagName("link"));
				var head = document.getElementsByTagName("head")[0];
				for (var i = 0; i < sheets.length; ++i) {
					var elem = sheets[i];
					var parent = elem.parentElement || head;
					parent.removeChild(elem);
					var rel = elem.rel;
					if (elem.href && typeof rel != "string" || rel.length == 0 || rel.toLowerCase() == "stylesheet") {
						var url = elem.href.replace(/(&|\?)_cacheOverride=\d+/, '');
						elem.href = url + (url.indexOf('?') >= 0 ? '&' : '?') + '_cacheOverride=' + (new Date().valueOf());
					}
					parent.appendChild(elem);
				}
			}
			var protocol = window.location.protocol === 'http:' ? 'ws://' : 'wss://';
			var address = protocol + window.location.host + window.location.pathname + '/ws';
			var socket = new WebSocket(address);
			socket.onmessage = function (msg) {
				if (msg.data == 'reload') window.location.reload();
				else if (msg.data == 'refreshcss') refreshCSS();
			};
			if (sessionStorage && !sessionStorage.getItem('IsThisFirstTime_Log_From_LiveServer')) {
				console.log('Live reload enabled.');
				sessionStorage.setItem('IsThisFirstTime_Log_From_LiveServer', true);
			}
		})();
	}
	else {
		console.error('Upgrade your browser. This Browser is NOT supported WebSocket for Live-Reloading.');
	}
	// ]]>
</script>
</body>
</html>
