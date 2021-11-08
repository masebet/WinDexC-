# WinDexC-
latihan visual studio CLR

https://www.youtube.com/watch?v=4FGEe5qfOjU

ctrl+alt+x

using namespace System;
using namespace System::Windows::Forms;

[STAThreadAttribute]
void Main(array<String^>^ args) {
	Application::EnableVisualStyles();
	Application::SetCompatibleTextRenderingDefault(false);
	karebet::MyForm form;
	Application::Run(% form);
}


HEADER:ALGORITHM & TOKEN TYPE

{
  "alg": "HS256",
  "typ": "JWT"
}
PAYLOAD:DATA

{
   "appKey": "o0tjmmw9MuSn7ZJCqYBOyxrfwBJ9V3bEkDSa",
   "iat": 1635221355,
   "exp": 1635221455,
   "tokenExp": 1635721355
}
VERIFY SIGNATURE

HMACSHA256(
  base64UrlEncode(header) + "." +
  base64UrlEncode(payload),
  
pDsm3ElZLy2gjTtZ7N4r0867udj29BCfKlIY

)

eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJhcHBLZXkiOiJvMHRqbW13OU11U243WkpDcVlCT3l4cmZ3Qko5VjNiRWtEU2EiLCJpYXQiOjE2MzUzMTc4OTYsImV4cCI6MTYzOTMxNzg5NiwidG9rZW5FeHAiOjE2MzkzMTc4OTZ9.veJJSvKNiWNpWNwdhoRfbDD5P07Eg9HV_lBE885IohI
