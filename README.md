# ENCODER8TO3
![image](https://github.com/RESMIRNAIR/ENCODER3TO8/assets/154305926/824226c8-c767-44b5-ab35-26fed65b195e)
# Truth Table
![image](https://github.com/RESMIRNAIR/ENCODER3TO8/assets/154305926/e228c14b-b814-40c8-92eb-748d48570c04)
# Circuit Diagram
![image](https://github.com/RESMIRNAIR/ENCODER3TO8/assets/154305926/6fa5fe84-fe6f-472d-b9c0-e6dfa17413d3)
![image](https://github.com/RESMIRNAIR/ENCODER3TO8/assets/154305926/7d147e2a-ba03-4714-baee-17615c9c50c1)
## program
```
module encoder_8 8(d,a,b,c) ;
input [7:0]d;
output a,b,c;
or(a,d[4],d[5],d[6],d[7])
or(b,d[2],d[3],d[6],d[7]);
or(c,d[1],d[3],d[5],d[7])
endmodule
```
## output
![Screenshot (4)](https://github.com/TARUN-E-A/ENCODER8TO3/assets/163630871/8e4e1d45-1dbc-4ffe-852a-435686f0a9df)
