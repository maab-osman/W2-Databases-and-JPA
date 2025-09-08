# Databases Excercises PART 2 (bookstore2 branch)

## One-to-Many Relationship Implementation
[Part 2](bookstore)

This chapter adds a Category entity with a one-to-many relationship to Books.

### Features Added:
- Category entity with id and name attributes
- One-to-many relationship between Book and Category
- Category dropdown in book creation/edition forms
- Category display in book list page
- MySQL database integration

### Technical Details:
- Spring Data JPA with Hibernate
- MySQL database instead of H2 for production-ready implementation
- Proper form handling with category selection

### Database Setup on macOS:
Instead of XAMPP, I used Homebrew for MySQL installation on macOS:
```bash
# Install Homebrew package manager
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"

# Install MySQL
brew install mysql

# Start MySQL service
brew services start mysql

# Secure installation
mysql_secure_installation
