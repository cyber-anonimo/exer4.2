int main(){

int n1 = 0;
int n1 = 4,n2 = 1,n3 = 5;
	int menor, meio, maior;
	if (n1 < n2 && n1 < n3) {
	   menor = n1;
	   if (n2 < n3) {
		meio = n2;
                maior = n3;
	   } else {
		meio = n3;
                maior = n2;
	   }
	} else if (n2 < n1 && n2 < n3) {
	   menor = n2;
	   if (n1 < n3) {
		meio = n1;
                maior = n3;
	   } else {
		meio = n3;
                maior = n1;
	   }
	} else {
	   menor  = n3;
	   if (n1 < n2) {
		meio = n1;
                maior = n2;
	   } else {
		meio = n2;
                maior = n1;
	   }
	}
return menor;
}
