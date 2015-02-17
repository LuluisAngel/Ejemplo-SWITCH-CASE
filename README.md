# Ejemplo-SWITCH-CASE
Here's the code

        #include <iostream>
        using namespace std;
        // Luis Angel Aguilar Carrillo A01225421
        
        /*
        This is an activity:
        
        An Auto Insurance Program
        
        • Write a program to determine the cost of an automobile insurance
        premium, based on driver's age and the number of accidents that the
        driver has had.
        • The basic insurance charge is $500. There is a surcharge of $100 if the
        driver is under 25 and an additional surcharge for accidents:
         # of accidents Accident Surcharge
         1 50
         2 125
         3 225
         4 375
         5 575
         6 or more No insurance 
        
        */
        
        
        
        int main(){
        
        	int e, a, pago;
        
        	cout << "Cuantos años tienes?" << endl;
        	cin >> e;
        
        	if (e<25){
        
        		pago = 600;
        	}
        
        		else {
        			pago = 500;
        		}
        
        	cout << "Cuantos accidentes has tenido?" << endl;
        	cin >> a;
        
        	switch (a){
        
        		case 1: 
        		pago = pago + 50;
        		cout << "Debes de pagar $" << pago << endl; 
        		break;
        
        		case 2: 
        		pago = pago + 125;
        		cout << "Debes de pagar $" << pago << endl;
        		break;
        
        		case 3:
        		pago = pago + 225;
        		cout << "Debes de pagar $" << pago << endl;
        		break;
        
        		case 4:
        		pago = pago + 375;
        		cout << "Debes de pagar $" << pago << endl;
        		break;
        
        		case 5:
        		pago = pago + 575;
        		cout << "Debes de pagar $" << pago << endl;
        		break;
        
        		default:
        			cout << "No seguro por tener tantos accidentes" << endl;
        
        	}
        
        	return 0;
        }
