# **************************************************************************** #
#                                                                              #
#                                                         :::      ::::::::    #
#    Makefile                                           :+:      :+:    :+:    #
#                                                     +:+ +:+         +:+      #
#    By: nmetseem <marvin@42.fr>                    +#+  +:+       +#+         #
#                                                 +#+#+#+#+#+   +#+            #
#    Created: 2018/05/23 12:00:39 by nmetseem          #+#    #+#              #
#    Updated: 2018/06/30 18:11:21 by nmetseem         ###   ########.fr        #
#                                                                              #
# **************************************************************************** #

CFLAGS = -Wall -Werror -Wextra

NAME = libft.a

OBJ = ft_bzero.o ft_isdigit.o ft_strlen.o ft_tolower.o ft_memchr.o ft_memset.o ft_strstr.o ft_toupper.o ft_strclr.o ft_strnew.o ft_putchar.o ft_putstr.o ft_isalpha.o ft_isprint.o ft_isalnum.o ft_isascii.o ft_strdup.o ft_strcpy.o ft_putendl.o ft_putstr_fd.o ft_putchar_fd.o ft_strequ.o ft_strjoin.o ft_strchr.o ft_strrchr.o ft_memcmp.o ft_strcmp.o ft_strncmp.o ft_strncpy.o ft_memalloc.o ft_putnbr.o ft_putnbr_fd.o ft_strnequ.o ft_strsub.o ft_strcat.o ft_memdel.o ft_strdel.o ft_putendl_fd.o ft_strnstr.o ft_memcpy.o ft_strncat.o ft_strlcat.o ft_memccpy.o ft_strtrim.o ft_atoi.o ft_striter.o ft_striteri.o ft_strmap.o ft_strmapi.o ft_memmove.o ft_itoa.o ft_strsplit.o

all: $(NAME)

$(NAME): $(OBJ)
	ar rc $(NAME) $(OBJ)
	ranlib  $(NAME)

$(OBJ):
	gcc -c $*.c -o $@ $(CFLAGS)

clean:
	rm -f $(OBJ)

fclean: clean 
	rm -f $(NAME)

re : fclean all 
