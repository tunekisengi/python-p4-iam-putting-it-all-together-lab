# TODO List

## Task: Fix SQLAlchemy IntegrityError and Implement API Resources

### Step 1: Fix models.py
- [x] Change `_password_hash` column to `nullable=True`

### Step 2: Implement app.py resource classes
- [x] Implement Signup Resource (POST /signup)
- [x] Implement CheckSession Resource (GET /check_session)
- [x] Implement Login Resource (POST /login)
- [x] Implement Logout Resource (DELETE /logout)
- [x] Implement RecipeIndex Resource (GET/POST /recipes)

### Step 3: Run tests to verify
- [x] Run pytest to confirm all tests pass

