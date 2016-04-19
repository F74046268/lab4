A.
	main
	_Z7averageif
	_Z7averagePdRd

B.
	1 8
	4 8
	4 8
	8 8

	因為各資料型態在記憶體中所佔的資料量
		char	佔 1 byte
		int		佔 4 byte
		float	佔 4 byte
		double	佔 8 byte

	而我的電腦是64位元,使用64位元來記載記憶體位址
	不論是那種資料型態的pointer,在記憶體內的位址都將佔用 8 byte
	所以pointer type的大小為 8 byte
