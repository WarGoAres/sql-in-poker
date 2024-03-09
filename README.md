# sql-in-poker
CREATE TABLE poker_cards (
    card_id INT PRIMARY KEY,
    suit VARCHAR(10),
    card_rank VARCHAR(5)
);


INSERT INTO poker_cards (card_id, suit,card_rank ) VALUES
(1, 'Spades', 'Ace'),
(2, 'Spades', '2'),
(3, 'Spades', '3'),
(4, 'Spades', '4'),
(5, 'Spades', '5'),
(6, 'Spades', '6'),
(7, 'Spades', '7'),
(8, 'Spades', '8'),
(9, 'Spades', '9'),
(10, 'Spades', '10'),
(11, 'Spades', 'Jack'),
(12, 'Spades', 'Queen'),
(13, 'Spades', 'King'),

(14, 'Hearts', 'Ace'),
(15, 'Hearts', '2'),
(16, 'Hearts', '3'),
(17, 'Hearts', '4'),
(18, 'Hearts', '5'),
(19, 'Hearts', '6'),
(20, 'Hearts', '7'),
(21, 'Hearts', '8'),
(22, 'Hearts', '9'),
(23, 'Hearts', '10'),
(24, 'Hearts', 'Jack'),
(25, 'Hearts', 'Queen'),
(26, 'Hearts', 'King'),

(27, 'Diamonds', 'Ace'),
(28, 'Diamonds', '2'),
(29, 'Diamonds', '3'),
(30, 'Diamonds', '4'),
(31, 'Diamonds', '5'),
(32, 'Diamonds', '6'),
(33, 'Diamonds', '7'),
(34, 'Diamonds', '8'),
(35, 'Diamonds', '9'),
(36, 'Diamonds', '10'),
(37, 'Diamonds', 'Jack'),
(38, 'Diamonds', 'Queen'),
(39, 'Diamonds', 'King'),

(40, 'Clubs', 'Ace'),
(41, 'Clubs', '2'),
(42, 'Clubs', '3'),
(43, 'Clubs', '4'),
(44, 'Clubs', '5'),
(45, 'Clubs', '6'),
(46, 'Clubs', '7'),
(47, 'Clubs', '8'),
(48, 'Clubs', '9'),
(49, 'Clubs', '10'),
(50, 'Clubs', 'Jack'),
(51, 'Clubs', 'Queen'),
(52, 'Clubs', 'King');


SELECT suit, card_rank
FROM poker_cards
WHERE card_id = 52;








