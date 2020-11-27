# provincias-panama
Mysql table of provinces of Panama with their respective flags.
Mysql tabla de provincias de panamá con sus respectivas banderas.

->Execute mysql command to create a table with the names, iso code and flags of the provinces of Panama.
->Ejecutar comando mysql para crear una tabla con los nombres, codigo iso y banderas de las provincias de Panamá.

CREATE TABLE `provincias` (
`id` int(11) NOT NULL AUTO_INCREMENT,
`name` varchar(16) DEFAULT NULL,
`iso` varchar(6) DEFAULT NULL,
`flag` varchar(32) DEFAULT NULL,
PRIMARY KEY (`id`)
) ENGINE=InnoDB DEFAULT CHARSET=latin1 AUTO_INCREMENT=1;

INSERT INTO `provincias` (`id`, `name`, `iso`, `flag`) VALUES ('1', 'Bocas del Toro', 'PAN-1', 'bocas-del-toro.png'), ('2', 'Coclé', 'PAN-2', 'cocle.png'), ('3', 'Colón', 'PAN-3', 'colon.png'), ('4', 'Chiriquí', 'PAN-4', 'chiriqui.png'), ('5', 'Darién', 'PAN-5', 'darien.png'), ('6', 'Herrera', 'PAN-6', 'herrera.png'), ('7', 'Los Santos', 'PAN-7', 'los-santos.png'), ('8', 'Panamá', 'PAN-8', 'panama.png'), ('9', 'Veraguas', 'PAN-9', 'veraguas.png'), ('10', 'Panamá Oeste', 'PAN-10', 'panama-oeste.png');

