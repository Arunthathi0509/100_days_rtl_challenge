module ripple_carry_adder_4bit(a,b,c,sum,cout
    );
	 input [3:0]a;
	 input [3:0]b;
	 input [3:0]c;
	 output [3:0]sum;
	 output cout;
	 wire w1,w2,w3;
	 full_adder1(.a(a[0]),.b(b[0]),.c(c[0]),.sum(sum[0]),.cout(w1));
	 full_adder2(.a(a[1]),.b(b[1]),.c(c[1]),.sum(sum[1]),.cout(w2));
	 full_adder3(.a(a[2]),.b(b[2]),.c(c[2]),.sum(sum[2]),.cout(w3));
	 full_adder4(.a(a[3]),.b(b[3]),.c(c[3]),.sum(sum[3]),.cout(cout));

endmodule
