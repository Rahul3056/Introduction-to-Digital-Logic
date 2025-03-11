Concept Overview
Digital logic is the foundation of digital electronics. It involves the use of binary values (0 and 1) to represent and manipulate data. The key elements in digital logic include logic gates, combinational circuits, and sequential circuits.

Key Topics Covered
✅ Binary System (0 and 1)
✅ Logic Levels (HIGH/LOW or TRUE/FALSE)
✅ Basic Logic Gates Overview (AND, OR, NOT)
✅ Truth Tables for Basic Gates
✅ Real-World Applications of Digital Logic

Example Verilog Code for Basic Logic Gates
odule basic_gates (
    input wire A, B,
    output wire AND_out,
    output wire OR_out,
    output wire NOT_A
);

// Logic gate implementations
assign AND_out = A & B;
assign OR_out = A | B;
assign NOT_A = ~A;

endmodule

 Testbench
module testbench;
    reg A, B;
    wire AND_out, OR_out, NOT_A;

    basic_gates uut (.A(A), .B(B), .AND_out(AND_out), .OR_out(OR_out), .NOT_A(NOT_A));

    initial begin
        $monitor("A=%b B=%b | AND=%b OR=%b NOT_A=%b", A, B, AND_out, OR_out, NOT_A);
        
        // Test cases
        A = 0; B = 0; #10;
        A = 0; B = 1; #10;
        A = 1; B = 0; #10;
        A = 1; B = 1; #10;

        $finish;
    end
endmodule
