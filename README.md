# Hello-world
const String operator+(const String& s)
{
this.len=len+s.len;
char * str=new char[this.len+1];
strcpy(str,this.rep);
strcat(str,s.rep);
String mystr(str);
delete [] str;
return mystr;
}

const String &operator+=(const String& s)
{
this.len+=s.len;
char * str=this.rep;
rep=new char[this.len=1];
strcpy(rep,str);
strcat(rep,s.rep);
delete []str;
return *this;
}
//这是一个简单的测试修改！（正常的修改）
//修改注释三
//修改注释四
//修改注释五
