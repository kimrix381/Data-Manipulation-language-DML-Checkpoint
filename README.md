# Data-Manipulation-language-DML-Checkpoint
-- Insert into clientes
INSERT INTO clientes (idcliente, nombre, direccion, telefono) VALUES
(1, 'Juan Perez', 'Calle Falsa 123', '555-1234'),
(2, 'Maria Gomez', 'Av. Siempre Viva 742', '555-5678');

-- Insert into productos
INSERT INTO productos (idproducto, descripcion, precio) VALUES
(1, 'Manzanas', 50),
(2, 'Naranjas', 40),
(3, 'Platanos', 30);

-- Insert into ventas
INSERT INTO ventas (idventa, idcliente, fecha) VALUES
(1, 1, '2024-05-01'),
(2, 2, '2024-05-02');

-- Insert into detalle_ventas
INSERT INTO detalle_ventas (idventa, idproducto, cantidad, precio) VALUES
(1, 1, 10, 50),
(1, 2, 5, 40),
(2, 3, 7, 30);
