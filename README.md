Conta-Bancaria
==============

public classe Conta {
 private double Saldo = 0;
public void sacar(double valor){
if (saldo >=valor)
saldo -= Valor;
}
}
public classe Especial extends Conta {
	private double limite;
	public void sacar (double valor) {
if (saldo + limite > = valor)
Saldo -= valor;
}
}


