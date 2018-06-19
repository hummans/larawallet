
# Lara Wallet

Larawallet is a wallet system package that allow you fast develop wallet system in your project.

## 1. Installation

Install the package with composer:

```bash
composer require nattaponra/larawallet
```

## 2. Run Migrations

Publish the migrations and config file with this artisan command:

```bash
php artisan vendor:publish --provider="nattaponra\LaraWallet\LaraWalletServiceProvider"
```
Run migration file to create database tables:

```bash
php artisan migrate
```
## 3. Wallet using with user model.

 Add 'HasWallet' trait in User model:

```bash
class User extends Authenticatable
{

    use HasWallet;
    use Notifiable;

    /**
     * The attributes that are mass assignable.
     *
     * @var array
     */
```
 
## 4. Using
 
