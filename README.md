deixe itens = [];
deixe bins = [];

função setup() {
criarCanvas(800, 400);
tamanho do texto(16);
textAlign(CENTRO, CENTRO);

// Criar lixeiras
bins.push(new Bin(150, 300, 'Orgânico', color(150, 75, 0)));
bins.push(new Bin(400, 300, 'Reciclável', color(0, 150, 255)));
bins.push(new Bin(650, 300, 'Rejeito', color(120)));

// Criar itens de lixo
itens.push(new TrashItem('Banana', 100, 100, 'Orgânico'));
itens.push(new TrashItem('Garrafa PET', 250, 100, 'Reciclável'));
itens.push(new TrashItem('Papel sujo', 400, 100, 'Rejeito'));
}

