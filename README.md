#include <iostream>
#include <Windows.h>

int main() {
	SetConsoleCP(1251);
	SetConsoleOutputCP(1251);
	
	std::string answ{};

	std::cout << "Мы идем по темному коридору заброшенной больницы и встречаем там человека в длинном плаще одетого в капюшон." << std::endl <<
		" И он задает вопрос: " << std::endl <<
	" -Ты заблудился? " << std::endl;
	
	std::cout << std::endl << "да/нет" << std::endl;
	std::cin >> answ;

	if (answ == "да") {
	std::cout << " Пойдем я покажу тебе выход от сюда бедняжка"
		<< std::endl;
	}

	else if (answ == "нет") {

	std::cout << " Тогда мне очень жаль."
			" Тебе видимо очень скучно живется. "
			" Начинает идти с ножом в нашу сторону"
			<< std::endl;
	}


	else {
	std::cout << " Развернувшись уходит..."
			<< std::endl;
	}

}
