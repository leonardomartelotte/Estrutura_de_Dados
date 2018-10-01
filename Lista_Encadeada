#include <stdio.h>
#include <stdlib.h>
struct lista {
      char nome[81];
      int mat;
      float p1,p2,p3;
      struct lista* prox;
};
typedef struct lista Lista;

Lista* lst_cria (void)
{
    return NULL;
}

Lista* lst_insere (Lista* l, int i,int j)
{
    Lista* novo = (Lista*) malloc(sizeof(Lista));
    novo->p1 = i;
    novo->p2 = i;
    novo->p3 = i;
    novo->mat = j;
    novo->prox = l;
    return novo;
}
void lst_imprime (Lista* l)
{
    Lista* p;
    for (p = l; p != NULL; p = p->prox)
    printf("info = %d\n", p->mat);
    printf("info = %d\n", p->p1);
    printf("info = %d\n", p->p2);
    printf("info = %d\n", p->p3);
    printf("info = %d\n", p->nome[0]);
}


int main (void)
    {
    Lista* l; /* declara uma lista não inicializada */
    l = lst_cria(); /* cria e inicializa lista como vazia */
    l = lst_insere(l, 23,2); /* insere na lista o elemento 23 */
    l = lst_insere(l, 45,3);
    lst_imprime (l);
 
    
}
