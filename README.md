# Animal---19
abstract class Animal {
    int expectativaDeVida;

    abstract void comer();

    abstract void andar();

    void dormir() {
        System.out.println("Estou dormindo");
    }
}

class Macaco extends Animal {

    @Override
    void comer() {
        System.out.println("O macaco está comendo");
    }

    @Override
    void andar() {
        System.out.println("O macaco está andando");
    }

    @Override
    void dormir() {
        System.out.println("O macaco está dormindo");
    }
}

class Humano extends Animal {

    @Override
    void comer() {
        System.out.println("O Humano está comendo");
    }

    @Override
    void andar() {
        System.out.println("O Humano está andando");
    }
}
