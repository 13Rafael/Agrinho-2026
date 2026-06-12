# Agrinho-2026
.mini-forest {
    display: flex;
    justify-content: center;
    align-items: flex-end;
    gap: 15px;
    height: 60px;
    margin-bottom: 25px;
}

.tree {
    font-size: 30px; /* Árvores pequenas */
    display: inline-block;
    transform-origin: bottom center;
    animation: sway 3s ease-in-out infinite alternate;
}

/* Variações de tempo de animação para as árvores parecerem naturais */
.tree-1 { animation-duration: 2.5s; animation-delay: 0.1s; }
.tree-2 { animation-duration: 3.2s; animation-delay: 0.4s; font-size: 35px; } /* Um pouco maior */
.tree-3 { animation-duration: 2.8s; animation-delay: 0.2s; }
.tree-4 { animation-duration: 3.5s; animation-delay: 0.6s; font-size: 28px; }

@keyframes sway {
    0% {
        transform: rotate(-3deg) scale(0.98);
    }
    100% {
        transform: rotate(3deg) scale(1.02);
    }
}
