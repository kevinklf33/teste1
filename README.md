git checkout kevinklf

# teste1
teste1  

#include <iostream>
#include <string>

using namespace std; 

int main() { 
//entrada
 float preco_item_1, preco_item_2, preco_item_3, percentual;
 string nome_item_1, nome_item_2, nome_item_3;
 float preco_final_1, preco_final_2, preco_final_3;
percentual = 0.9;
cout << "insira o nome do primeiro produto ";
cin >> nome_item_1;
cout << "insera o nome do segundo preduto ";
cin >> nome_item_2;
cout << "insira o nome do terceiro produto ";
cin >> nome_item_3;

cout << "insira o preco do(a) " << nome_item_1<< std::endl;
cin >> preco_item_1;
cout << "insira o preco do(a) " << nome_item_2<< std::endl;
cin >> preco_item_2;
cout << "insira o preco do(a) " << nome_item_3<< std::endl;
cin >> preco_item_3;
//processo

preco_final_1 = preco_item_1 * percentual;
preco_final_2 = preco_item_2 * percentual;
preco_final_3 = preco_item_3 * percentual;

cout << "O valor de " << nome_item_1<< " com o desconto eh "<< preco_final_1<< std::endl;
cout << "O valor de " << nome_item_2<< " com o desconto eh "<< preco_final_2<< std::endl;
cout << "O valor de " << nome_item_3<< " com o desconto eh "<< preco_final_3<< std::endl;
}
