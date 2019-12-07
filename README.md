# MiniLang_compil
This is a repository for a school Project, the Goal is to create a compiler for a language called MiniLang
%{

%}
chiffre[0-9]
const [1-9][0-9]*|0
vide [ \t]+
saut_ligne [\n]
idf [A-Z]([_]?[a-z0-9])*.{1-12}
int [- | +]? [1-9][0-9]*
float [- | +]? ([1-9][0-9]*|0)\.([0-9]*[1-9])
bool "false" | "true" | "TRUE" | "FALSE"
varint "INT" | "int"
varfloat "FLOAT" | "float"
varbool "bool" | "BOOL"
const_int "const int"|"CONST INT"
const_float "const float" | "CONST FLOAT"
op "-" | "+" | "/" | "*"
rat "<" | ">" | "<=" | ">=" | "==" |"<>"
comment "{"[^}]*"}"






%%
%%
