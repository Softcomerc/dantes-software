//# dantes-software
//aqui serão depositados os códigos dos programas
//primeira parte feita

package imagem;
import java.awt.BorderLayout;
import java.awt.Dimension;
import java.awt.Font;
import java.awt.Frame;
import java.awt.GridLayout;
import java.awt.Window;
import java.awt.event.ActionEvent;
import java.awt.event.ActionListener;
import java.text.ParseException;

import javax.swing.ImageIcon;
import javax.swing.JButton;
import javax.swing.JFormattedTextField;
import javax.swing.JFrame;
import javax.swing.JLabel;
import javax.swing.JMenu;
import javax.swing.JMenuBar;
import javax.swing.JMenuItem;
import javax.swing.JOptionPane;
import javax.swing.JPanel;
import javax.swing.JScrollPane;
import javax.swing.JTable;
import javax.swing.JTextField;
import javax.swing.table.DefaultTableModel;
import javax.swing.text.MaskFormatter;


public class Projeto {
	static JFrame telaprincipal = new JFrame("TREINAMENTO");
	static JFrame telainicial = new JFrame("TELA INICIAL");
	static JFrame telamenu = new JFrame("MENU");
	static JFrame telacadastro = new JFrame("CADASTRO");
	static JFrame telatelefone = new JFrame("TELEFONE");
	static JFrame telaencereco = new JFrame("ENDERECO");
	static JFrame telacliente = new JFrame("CLIENTE");
	static JFrame telafiliais = new JFrame("FILIAIS");
	static JFrame telafornecedor = new JFrame("FORNECEDOR");
	static JFrame telaproduto = new JFrame("PRODUTO");
	static JFrame telaconsulta = new JFrame("CONSULTA");
	static JFrame telarelatorio = new JFrame("RELATÓRIO");
	static JFrame telatutorial = new JFrame("TUTORIAL");
	static JFrame telaimpressora = new JFrame("IMPRESSORA");
	static JFrame telasistemas = new JFrame("SISTEMAS");
	static JFrame telaxml = new JFrame("XML");
	static JFrame telabackup = new JFrame("BACKUP");
	static JFrame telastatus = new JFrame("STATUS");
	static JFrame telapontuação = new JFrame("PONTUAÇÃO");
	static JFrame telaranking = new JFrame("RANKING");
	static JFrame telavendas = new JFrame("VENDAS");
	static JFrame telainstalação = new JFrame("INSTALAÇÃO");
	static JFrame telapedidodevenda = new JFrame("PEDIDO DE VENDA");
	static JFrame teladevolucao = new JFrame("DEVOLUÇÃO");
	static JFrame telaconfiguracao = new JFrame("CONFIGURAÇÃO");
	static JFrame telaping = new JFrame("PING");
	static JFrame telaerros = new JFrame("ERROS");
	static JFrame telanotas = new JFrame("NOTAS");
	static JFrame telaajuda = new JFrame("AJUDA");
	static JFrame telajogo = new JFrame("TRAINING OF GAME");
	static JFrame telascript = new JFrame("SCRIPT");
	
	static JButton login = new JButton("LOGIN");
	static JButton entrar = new JButton("ENTRAR");
	static JButton corrigir = new JButton("CORRIGIR");
	static JButton inicio = new JButton("INICIO");
	static JButton proximo = new JButton("PROXIMO");
	static JButton anterior = new JButton("ANTERIOR");
	static JButton salvar = new JButton("SALVAR");
	static JButton voltar = new JButton("VOLTAR");
	static JButton voltar0 = new JButton("VOLTAR");
	static JButton voltar1 = new JButton("VOLTAR");
	static JButton voltar2 = new JButton("VOLTAR");
	static JButton voltar3 = new JButton("VOLTAR");
	static JButton voltar4 = new JButton("VOLTAR");
	static JButton voltar5 = new JButton("VOLTAR");
	static JButton voltar6 = new JButton("VOLTAR");
	static JButton voltar7 = new JButton("VOLTAR");
	static JButton voltar8 = new JButton("VOLTAR");
	static JButton voltar9 = new JButton("VOLTAR");
	static JButton voltar10 = new JButton("VOLTAR");
	static JButton gravar = new JButton("GRAVAR");
	static JButton gravar0 = new JButton("GRAVAR");
	static JButton gravar1 = new JButton("GRAVAR");
	static JButton gravar2 = new JButton("GRAVAR");
	static JButton gravar3 = new JButton("GRAVAR");
	static JButton gravar4 = new JButton("GRAVAR");
	static JButton cadastro = new JButton("CADASTRO");
	static JButton telefone = new JButton("TELEFONE");
	static JButton endereco = new JButton("ENDEREÇO");
	static JButton cliente = new JButton("CLIENTE");
	static JButton filiais = new JButton("FILIAIS");
	static JButton fornecedor = new JButton("FORNECEDOR");
	static JButton produto = new JButton("PRODUTO");
	static JButton consulta = new JButton("CONSULTA");
	static JButton relatório = new JButton("RELATÓRIO");
	static JButton tutorial = new JButton("TUTORIAL");
	static JButton impressora = new JButton("IMPRESSORA");
	static JButton sistemas = new JButton("SISTEMAS");
	static JButton xml = new JButton("XML");
	static JButton backup = new JButton("BACKUP");
	static JButton status = new JButton("STATUS");
	static JButton pontuacao = new JButton("PONTUAÇÃO");
	static JButton ranking = new JButton("RANKING");
	static JButton vendas = new JButton("VENDAS");
	static JButton instalacao = new JButton("INSTALAÇÃO");
	static JButton pedidodevenda = new JButton("PEDIDO DE VENDA");
	static JButton devolucao = new JButton("DEVOLUÇÃO");
	static JButton configuracao = new JButton("CONFIGURAÇÃO");
	static JButton erros = new JButton("ERROS");
	static JButton notas = new JButton("NOTAS");
	static JButton ajuda = new JButton("AJUDA");
	static JButton jogo = new JButton("JOGO");
	static JButton ping = new JButton("PING");
	static JButton script = new JButton("SCRIPT");
	


static void telaprincipal() {

	telaprincipal.setTitle("TREINAMENTO");
	telaprincipal.setSize(600, 400);
	telaprincipal.setLocationRelativeTo(null);
	telaprincipal.setResizable(false);
	telaprincipal.setVisible(true);
	telaprincipal.setDefaultCloseOperation(JFrame.EXIT_ON_CLOSE);
	
	
} 
static void telaincial() {

	Frame telaincial;
	telaincial.setTitle("TELA PRINCIPAL");
	telaincial.setSize(600, 400);
	telaincial.setLocationRelativeTo(null);
	telaincial.setResizable(false);
	telaincial.setVisible(true);
	telaincial.setDefaultCloseOperation(JFrame.EXIT_ON_CLOSE);
	
	
} 
static void telamenu() {

	telamenu.setTitle("MENU");
	telamenu.setSize(600, 400);
	telamenu.setLocationRelativeTo(null);
	telamenu.setResizable(false);
	telamenu.setVisible(true);
	telamenu.setDefaultCloseOperation(JFrame.EXIT_ON_CLOSE);
	
	
} 
static void telacadastro() {

	telacadastro.setTitle("CADASTRO");
	telacadastro.setSize(600, 400);
	telacadastro.setLocationRelativeTo(null);
	telacadastro.setResizable(false);
	telacadastro.setVisible(true);
	telacadastro.setDefaultCloseOperation(JFrame.EXIT_ON_CLOSE);
	
	
} 
static void telatelefone() {

	telatelefone.setTitle("TELEFONE");
	telatelefone.setSize(600, 400);
	telatelefone.setLocationRelativeTo(null);
	telatelefone.setResizable(false);
	telatelefone.setVisible(true);
	telatelefone.setDefaultCloseOperation(JFrame.EXIT_ON_CLOSE);
	
	
} 
static void telaendereco() {

	Frame telaendereco;
	telaendereco.setTitle("ENDEREÇO");
	telaendereco.setSize(600, 400);
	telaendereco.setLocationRelativeTo(null);
	telaendereco.setResizable(false);
	telaendereco.setVisible(true);
	telaendereco.setDefaultCloseOperation(JFrame.EXIT_ON_CLOSE);
	
	
}
static void telacliente() {

	telacliente.setTitle("CLIENTE");
	telacliente.setSize(600, 400);
	telacliente.setLocationRelativeTo(null);
	telacliente.setResizable(false);
	telacliente.setVisible(true);
	telacliente.setDefaultCloseOperation(JFrame.EXIT_ON_CLOSE);
	
	
}
static void telafiliais() {

	telafiliais.setTitle("FILIAIS");
	telafiliais.setSize(600, 400);
	telafiliais.setLocationRelativeTo(null);
	telafiliais.setResizable(false);
	telafiliais.setVisible(true);
	telafiliais.setDefaultCloseOperation(JFrame.EXIT_ON_CLOSE);
	
	
}
static void telafonrecedor() {

	Frame telafonrecedor;
	telafonrecedor.setTitle("FORNECEDOR");
	telafonrecedor.setSize(600, 400);
	telafonrecedor.setLocationRelativeTo(null);
	telafonrecedor.setResizable(false);
	telafonrecedor.setVisible(true);
	telafonrecedor.setDefaultCloseOperation(JFrame.EXIT_ON_CLOSE);
	
	
}
static void telaproduto() {

	telaproduto.setTitle("PRODUTO");
	telaproduto.setSize(600, 400);
	telaproduto.setLocationRelativeTo(null);
	telaproduto.setResizable(false);
	telaproduto.setVisible(true);
	telaproduto.setDefaultCloseOperation(JFrame.EXIT_ON_CLOSE);
	
	
}
static void telaconsulta() {

	telaconsulta.setTitle("CONSULTA");
	telaconsulta.setSize(600, 400);
	telaconsulta.setLocationRelativeTo(null);
	telaconsulta.setResizable(false);
	telaconsulta.setVisible(true);
	telaconsulta.setDefaultCloseOperation(JFrame.EXIT_ON_CLOSE);
	
	
}
static void telarelatorio() {

	telarelatorio.setTitle("RELATÓRIO");
	telarelatorio.setSize(600, 400);
	telarelatorio.setLocationRelativeTo(null);
	telarelatorio.setResizable(false);
	telarelatorio.setVisible(true);
	telarelatorio.setDefaultCloseOperation(JFrame.EXIT_ON_CLOSE);
	
	
}
static void telatutorial() {

	telatutorial.setTitle("TUTORIAL");
	telatutorial.setSize(600, 400);
	telatutorial.setLocationRelativeTo(null);
	telatutorial.setResizable(false);
	telatutorial.setVisible(true);
	telatutorial.setDefaultCloseOperation(JFrame.EXIT_ON_CLOSE);
	
	
}
static void telaimpressora() {

	telaimpressora.setTitle("IMPRESSORA");
	telaimpressora.setSize(600, 400);
	telaimpressora.setLocationRelativeTo(null);
	telaimpressora.setResizable(false);
	telaimpressora.setVisible(true);
	telaimpressora.setDefaultCloseOperation(JFrame.EXIT_ON_CLOSE);
	
	
}
static void telasistemas() {

	telasistemas.setTitle("SISTEMAS");
	telasistemas.setSize(600, 400);
	telasistemas.setLocationRelativeTo(null);
	telasistemas.setResizable(false);
	telasistemas.setVisible(true);
	telasistemas.setDefaultCloseOperation(JFrame.EXIT_ON_CLOSE);
	
	
}
static void telaxml() {

	telaxml.setTitle("XML");
	telaxml.setSize(600, 400);
	telaxml.setLocationRelativeTo(null);
	telaxml.setResizable(false);
	telaxml.setVisible(true);
	telaxml.setDefaultCloseOperation(JFrame.EXIT_ON_CLOSE);
	
	
}
static void telabackup() {

	telabackup.setTitle("BACKUP");
	telabackup.setSize(600, 400);
	telabackup.setLocationRelativeTo(null);
	telabackup.setResizable(false);
	telabackup.setVisible(true);
	telabackup.setDefaultCloseOperation(JFrame.EXIT_ON_CLOSE);
	
	
}
static void telastatus() {

	telastatus.setTitle("STATUS");
	telastatus.setSize(600, 400);
	telastatus.setLocationRelativeTo(null);
	telastatus.setResizable(false);
	telastatus.setVisible(true);
	telastatus.setDefaultCloseOperation(JFrame.EXIT_ON_CLOSE);
	
	
}
static void telapontuacao() {

	Frame telapontuacao;
	telapontuacao.setTitle("PONTUAÇÃO");
	telapontuacao.setSize(600, 400);
	telapontuacao.setLocationRelativeTo(null);
	telapontuacao.setResizable(false);
	telapontuacao.setVisible(true);
	telapontuacao.setDefaultCloseOperation(JFrame.EXIT_ON_CLOSE);
	
	
}
static void telaranking() {

	telaranking.setTitle("RANKING");
	telaranking.setSize(600, 400);
	telaranking.setLocationRelativeTo(null);
	telaranking.setResizable(false);
	telaranking.setVisible(true);
	telaranking.setDefaultCloseOperation(JFrame.EXIT_ON_CLOSE);
	
	
}
static void telavendas() {

	telavendas.setTitle("VENDAS");
	telavendas.setSize(600, 400);
	telavendas.setLocationRelativeTo(null);
	telavendas.setResizable(false);
	telavendas.setVisible(true);
	telavendas.setDefaultCloseOperation(JFrame.EXIT_ON_CLOSE);
	
	
}
static void telainstalacao() {

	Frame telainstalacao;
	telainstalacao.setTitle("INSTALAÇÃO");
	telainstalacao.setSize(600, 400);
	telainstalacao.setLocationRelativeTo(null);
	telainstalacao.setResizable(false);
	telainstalacao.setVisible(true);
	telainstalacao.setDefaultCloseOperation(JFrame.EXIT_ON_CLOSE);
	
	
}
static void telapedidodevenda() {

	telapedidodevenda.setTitle("PEDIDO DE VENDA");
	telapedidodevenda.setSize(600, 400);
	telapedidodevenda.setLocationRelativeTo(null);
	telapedidodevenda.setResizable(false);
	telapedidodevenda.setVisible(true);
	telapedidodevenda.setDefaultCloseOperation(JFrame.EXIT_ON_CLOSE);
	
	
}
static void telaconfiguracao() {

	telaconfiguracao.setTitle("CONFIGURAÇÃO");
	telaconfiguracao.setSize(600, 400);
	telaconfiguracao.setLocationRelativeTo(null);
	telaconfiguracao.setResizable(false);
	telaconfiguracao.setVisible(true);
	telaconfiguracao.setDefaultCloseOperation(JFrame.EXIT_ON_CLOSE);
	
	
}
static void teladevolucao() {

	teladevolucao.setTitle("DEVOLUÇÃO");
	teladevolucao.setSize(600, 400);
	teladevolucao.setLocationRelativeTo(null);
	teladevolucao.setResizable(false);
	teladevolucao.setVisible(true);
	teladevolucao.setDefaultCloseOperation(JFrame.EXIT_ON_CLOSE);
	
	
}
static void telaerros() {

	telaerros.setTitle("ERROS");
	telaerros.setSize(600, 400);
	telaerros.setLocationRelativeTo(null);
	telaerros.setResizable(false);
	telaerros.setVisible(true);
	telaerros.setDefaultCloseOperation(JFrame.EXIT_ON_CLOSE);
	
	
}
static void telanotas() {

	telanotas.setTitle("NOTAS");
	telanotas.setSize(600, 400);
	telanotas.setLocationRelativeTo(null);
	telanotas.setResizable(false);
	telanotas.setVisible(true);
	telanotas.setDefaultCloseOperation(JFrame.EXIT_ON_CLOSE);
	
	
}
static void telaajuda() {

	telaajuda.setTitle("AJUDA");
	telaajuda.setSize(600, 400);
	telaajuda.setLocationRelativeTo(null);
	telaajuda.setResizable(false);
	telaajuda.setVisible(true);
	telaajuda.setDefaultCloseOperation(JFrame.EXIT_ON_CLOSE);
	
	
}
static void telaping() {

	telaping.setTitle("PING");
	telaping.setSize(600, 400);
	telaping.setLocationRelativeTo(null);
	telaping.setResizable(false);
	telaping.setVisible(true);
	telaping.setDefaultCloseOperation(JFrame.EXIT_ON_CLOSE);
	
	
}
static void telajogo() {

	telajogo.setTitle("TRAINING OF GAME");
	telajogo.setSize(600, 400);
	telajogo.setLocationRelativeTo(null);
	telajogo.setResizable(false);
	telajogo.setVisible(true);
	telajogo.setDefaultCloseOperation(JFrame.EXIT_ON_CLOSE);
	
	
}
static void telascript() {

	Frame telascrip;
	telascrip.setTitle("SCRIPT");
	telascrip.setSize(600, 400);
	telascrip.setLocationRelativeTo(null);
	telascrip.setResizable(false);
	telascrip.setVisible(true);
	telascrip.setDefaultCloseOperation(JFrame.EXIT_ON_CLOSE);
	
	
}

	public static void main(String[] args) {
		

	}

}

