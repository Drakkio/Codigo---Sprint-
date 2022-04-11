#include <iostream>

using namespace std;

int main(void)
{

int quad_alpha=1, quad_bravo=2, quad_charley=3, quad_elgar=4, quad_frey=5, quad_garen=6, pix,pag=0;
char nome,temp_ini,temp_sai,cpf[10];

cout << "Horarios das quadras diponiveis são: \n";

cout <<"Data: 13/05\n - 08:30:00 as 12:00:00\n - Periodo matutino\n - Quadra Alpha (Disponivel)\n" << quad_alpha; 
		cout <<" \nData: 14/05\n - 12:30:00 as 16:00:00\n - Periodo da tarde\n - Quadra Bravo (Disponivel)\n"<< quad_bravo;
				cout <<" \nData: 15/05\n -16:30:00 as 21:30:00\n - Periodo Noturno\n - Quadra Charley (Disponivel)\n"<< quad_charley;
				     cout <<" \nData: 16/05\n - 08:30:00 as 12:00:00\n - Periodo matutino\n - Quadra Alpha (Disponivel)\n"<< quad_elgar; 
		                    cout <<" \nData: 17/05\n - 12:30:00 as 16:00:00\n - Periodo da tarde\n - Quadra Bravo (Disponivel)\n"<< quad_frey;
				                    cout <<" \nData: 18/05\n -16:30:00 as 21:30:00\n - Periodo Noturno\n - Quadra Charley (Disponivel)\n"<< quad_garen;
               
               
               
cout<<"\nReserva da Quadra, \n  Por favor digite numero da Quadra Escolhida:   1=sim 2=nao ";


       if (quad_alpha !=0){                 //estrutura if tem que ser reavalida
    
        cout<< quad_alpha;
}
    else
    
        if(quad_bravo != 0){
            
            cout<<quad_bravo;
}
    else
    
       if(quad_charley != 0){
                
         cout<<quad_charley;
}
    else
         if(quad_elgar != 0){
                    
            cout<< quad_elgar;
}                
    else
         if(quad_frey != 0){
                        
            cout<<quad_frey;
}                    
    else
        if(quad_garen != 0){
                        
        cout<< quad_garen;
        
}
        else("\n\nSelecionar uma Quadra para reserva, Por favor!!!");

        
        
        
        cout<<"\nRegistro do nome do Usuario:   ";
            cin>>nome;
      
                cout<<"\n Numero do CPF do Usuario: ";
                    cin>>cpf;
                         
                         
                         
                
    cout<<"\n   Sistema de Pagamento: ";
    
    if(pix != 0){                                       //estrutura if tem que ser reavalida
        
        cout<<" \n Por Favor digite sua chave, email, celular e/ou CPF:    ";
            cin>> pix;
            
                 
            cout<<"Deseja utilizar outro meio de pagamento?:  1= Sim, 2=Nao\n";
                cin>>pag;
                
    }
        else 
        
        {
            if(pix == 0)
            cout<<" Pagemento Mal-sucedido, por favor retorne e realiza o pagamento";
    }       
            
        

    cout<<"\n Sistema de Utilização da Quadra";
        
        cout<<"\nTempo de utilização Quadra: ";
            cin>>temp_ini;
            
                cout<<"\nSaida do cliente: ";
                    cin>>temp_sai;
            
                
       
return 0;


}
