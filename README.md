# turkey
import pygame

pygame.init()
pygame.display.set_caption("turkey!")
screen = pygame.display.set_mode((1000,1000))

while(1):
    screen.fill((0,0,0))
    pygame.draw.circle(screen, (128, 89, 31), (470, 600), 200)
    pygame.draw.ellipse(screen, (128,89,31), (400,300,150,200))
    pygame.draw.ellipse(screen, (0, 0, 0), (400,300, 150,200), 2)
   
    pygame.display.flip()
