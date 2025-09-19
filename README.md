# Atividade- Turma 2B
Aluno Julio Cesar Rodrigues de Arruda Matricula 01841484


class Console :
    marca = "..."
    modelo = "..."
    def definir_marca(self, nova_marca):
        self.marca = nova_marca
    def definir_modelo(self, novo_modelo):
        self.modelo = novo_modelo

meu_console = Console()
meu_console.definir_marca("Playstation")
meu_console.definir_modelo("PS4")

print("Marca:", meu_console.marca)
print("Modelo:", meu_console.modelo)
