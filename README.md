# Bank-App-Project
class MainAccount:
    def _init_(self, initial_amount): 
        self._balance = initial_amount
        
    def display_account_balance(self):
        print(f"Curent balance: {self._balance}")
        
        
main_account = MainAccount(1000000)
main_account.display_account_balance()
