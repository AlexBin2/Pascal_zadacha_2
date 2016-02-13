# Pascal_zadacha_2
Zadacha_2

Program Zadacha2;
var 
a,b,d,k: integer;
x,y: real;
begin
  write('a:');
	readln(a);
	write('b:');
	readln(b);
	write('d:');
	readln(d);
	if (a > d) and (a < 15.3) then
	begin 
	x:=((2*a)*(2*a))-((3*b)*(3*b));
	y:=a-d;
	k:=1;
	end
	else 
	begin
	x:=sqrt(abs(a-b))+d;
	y:=10.5*b;
	k:=2;
	end;
	write('x:');
	writeln(x);
	write('y:');
	writeln(y);
	write('k:');
	writeln(k);
end.
