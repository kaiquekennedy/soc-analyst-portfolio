RELATÓRIO DE INCIDENTE – ANALISTA SOC

1. Resumo do Incidente - 
Data: 2026-05-28
Analista: Kaique Kennedy
Tipo de alerta: Tentativa de PIX não autorizada
Severidade: Crítica
 
2. Descrição - 
Tentativa de PIX não autorizada com uso de session_id válido fora do contexto original, com a possibilidade de um sequestro de sessão.
O incidente contou com três tentativas (em um período curto, em três minutos, entre 02:11PM e 02:13 PM), sendo a terceira tentativa bloqueada de forma automática. Além disso, o incidente foi gerado na ferramenta SecurityOne.
 
3. Investigação - 
IP de Origem
185.37.355.11
Destino
Utilização de seção de Tokens/ Sequestro de sessão.

Observações - 
•	Não houve evidência de comprometimento interno da infraestrutura do banco.
•	Endereço IP externo suspeito
•	Tentativa não autorizada foi bloqueada de forma automática

Ações Realizadas - 
•	Os tokens ativos do usuário foram revogados
•	As credenciais foram redefinidas
 
5. Conclusões - 
Não houve evidência de comprometimento interno durante a tentativa de PIX não autorizada.
 
6. Recomendações - 
•	Analisar possível malware no dispositivo
•	Revalidar dispositivos confiáveis
•	Bloquear padrões similares de ataque
•	Validar reputação do IP em ferramentas de threat intelligence.
 
7. Status do Incidente - 
Fechado 
 
