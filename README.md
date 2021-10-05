# WinDexC-
latihan visual studio CLR

https://www.youtube.com/watch?v=4FGEe5qfOjU

using namespace System;
using namespace System::Windows::Forms;

[STAThreadAttribute]
void Main(array<String^>^ args) {
	Application::EnableVisualStyles();
	Application::SetCompatibleTextRenderingDefault(false);
	karebet::MyForm form;
	Application::Run(% form);
}
