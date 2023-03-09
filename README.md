# sumof
Scanner sc = new Scanner(System.in);
		int a = sc.nextInt();
		int b = sc.nextInt();
		System.out.println(sumOf(a,b));
	}
	static int sumOf(int a, int b) {
		int sum = 0;
		for(int i =a; i <= b; i++) {
			sum += i;
		}
		return sum;
	}
}
