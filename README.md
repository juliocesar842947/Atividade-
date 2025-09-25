# Atividade- Turma 2B
Aluno Julio Cesar Rodrigues de Arruda Matricula 01841484
class Console :
    def exibir_marca(self,marca):
        self.marca = marca

    def exibir_modelo(self,modelo):
        self.modelo = modelo


meu_console = Console ()
meu_console.marca = ("Sony")
meu_console.modelo = ("PS4")
 
print(f"O console é um {meu_console.modelo} da {meu_console.marca}.")
