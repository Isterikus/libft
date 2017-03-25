Our first project.
To compile write "make" and then use libft.a with your main.

Mine own library libft with standart C and other functions:
long int			ft_atoi(const char *str);\n
void					ft_bzero(void *s, size_t n);\n
int						ft_isalnum(int c);\n
int						ft_isalpha(int c);\n
int						ft_isascii(int c);\n
int						ft_isdigit(int c);\n
int						ft_isprint(int c);\n
char					*ft_itoa(long long int n);\n
void					*ft_memalloc(size_t size);\n
void					*ft_memccpy(void *d, const void *s, int c, size_t n);\n
void					*ft_memchr(const void *s, int c, size_t n);\n
int						ft_memcmp(const void *s1, const void *s2, size_t n);\n
void					*ft_memcpy(void *dst, const void *src, size_t n);\n
void					ft_memdel(void **ap);\n
void					*ft_memmove(void *dst, const void *src, size_t len);\n
void					*ft_memset(void *b, int c, size_t len);\n
void					ft_putchar(char c);\n
void					ft_putchar_fd(char c, int fd);\n
void					ft_putendl(char const *s);\n
void					ft_putendl_fd(char const *s, int fd);\n
void					ft_putnbr(long long int i);\n
void					ft_putnbr_fd(int n, int fd);\n
void					ft_putstr(char const *s);\n
void					ft_putstr_fd(char const *s, int fd);\n
char					*ft_strcat(char *s1, const char *s2);\n
char					*ft_strchr(const char *s, int c);\n
void					ft_strclr(char *s);\n
int						ft_strcmp(const char *s1, const char *s2);\n
char					*ft_strcpy(char *dst, const char *src);\n
void					ft_strdel(char **as);\n
char					*ft_strdup(const char *s1);\n
int						ft_strequ(char const *s1, char const *s2);\n
void					ft_striter(char *s, void (*f)(char *));\n
void					ft_striteri(char *s, void (*f)(unsigned int, char *));\n
char					*ft_strjoin(char const *s1, char const *s2);\n
char					*ft_strjoin2(char const *s1, char const *s2);\n
size_t				ft_strlcat(char *dst, const char *src, size_t size);\n
size_t				ft_strlen(const char *s);\n
char					*ft_strmap(char const *s, char (*f)(char));\n
char					*ft_strmapi(char *s, char (*f)(unsigned int, char));\n
char					*ft_strncat(char *s1, const char *s2, size_t n);\n
int						ft_strncmp(const char *s1, const char *s2, size_t n);\n
char					*ft_strncpy(char *dst, const char *src, size_t len);\n
int						ft_strnequ(char const *s1, char const *s2, size_t n);\n
char					*ft_strnew(size_t size);\n
char					*ft_strnstr(const char *big, char *little, size_t len);\n
char					*ft_strrchr(const char *s, int c);\n
char					**ft_strsplit(char const *s, char c);\n
char					*ft_strstr(const char *big, const char *little);\n
char					*ft_strsub(char *s, unsigned int start, size_t len);\n
char					*ft_strtrim(char const *s);\n
int						ft_tolower(int c);\n
int						ft_toupper(int c);\n
size_t				ft_strlcpy(char *dst, const char *src, size_t size);\n
t_list				*ft_lstnew(void const *content, size_t content_size);\n
void					ft_lstadd(t_list **alst, t_list *new);\n
void					ft_lstdel(t_list **alst, void (*del)(void*, size_t));\n
void					ft_lstdelone(t_list **alst, void (*del)(void*, size_t));\n
void					ft_lstiter(t_list *lst, void (*f)(t_list *elem));\n
t_list				*ft_lstmap(t_list *lst, t_list *(*f)(t_list *elem));\n
