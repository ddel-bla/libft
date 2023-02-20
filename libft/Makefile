# **************************************************************************** #
#                                                                              #
#                                                         :::      ::::::::    #
#    Makefile                                           :+:      :+:    :+:    #
#                                                     +:+ +:+         +:+      #
#    By: ddel-bla <ddel-bla@student.42madrid.com    +#+  +:+       +#+         #
#                                                 +#+#+#+#+#+   +#+            #
#    Created: 2023/01/09 17:23:53 by ddel-bla          #+#    #+#              #
#    Updated: 2023/02/15 16:02:59 by ddel-bla         ###   ########.fr        #
#                                                                              #
# **************************************************************************** #

SRC				=	ft_isalpha.c ft_isdigit.c ft_isalnum.c \
					ft_isascii.c ft_isprint.c ft_strlen.c \
					ft_memset.c ft_bzero.c ft_memcpy.c \
					ft_memmove.c ft_strlcpy.c ft_strlcat.c \
					ft_toupper.c ft_tolower.c ft_strchr.c \
					ft_strrchr.c ft_strcmp.c ft_strncmp.c \
					ft_memchr.c ft_memcmp.c ft_strnstr.c \
					ft_atoi.c ft_calloc.c ft_strdup.c \
					ft_substr.c ft_strjoin.c ft_strtrim.c \
					ft_split.c ft_itoa.c ft_strmapi.c \
					ft_striteri.c ft_putchar_fd.c ft_putstr_fd.c \
					ft_putendl_fd.c ft_putnbr_fd.c

SRCB			=	ft_lstnew.c ft_lstadd_front.c ft_lstsize.c \
					ft_lstlast.c ft_lstadd_back.c ft_lstdelone.c \
					ft_lstclear.c ft_lstiter.c ft_lstmap.c

OBJ				=	$(SRC:.c=.o)

OBJB			=	$(SRCB:.c=.o)

LIB				=	ar rcs

RM				=	rm -f

CFLAGS			=	-Wall -Wextra -Werror

NAME			=	libft.a

$(NAME):		$(OBJ)
				$(LIB) $(FLAGS) $(NAME) $(OBJ)

all:			$(NAME)

bonus:			${OBJ} ${OBJB}
				$(LIB) ${NAME} ${OBJB}

clean:			
				$(RM) $(OBJ) $(OBJB)

fclean:			clean
				$(RM) $(NAME)

re:				fclean all bonus

.PHONY: all clean fclean re
