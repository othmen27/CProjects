# Memory Mastery Roadmap    
> **Language**: C
> **Prerequisites**: Basic programming knowledge (variables, loops, functions)  
> **Goal**: Eliminate fear of memory, pointers, and systems-level thinking—and gain deep intuition for how programs actually work.

---

##  Tier 1 — Foundations *(Easy | Days 1–4)*  
**Goal**: Stop being scared of memory & pointers.

### 1. Pointer Playground  
**What you build**:  
A program that prints, for `int`, `double`, and `char`:
- Variable value  
- Variable address  
- Pointer value  
- Dereferenced pointer value  
- Double pointer (pointer-to-pointer) behavior  

**Key concepts**:  
- Stack memory layout  
- `&` (address-of) vs `*` (dereference)  
- Pointer indirection  

**Time**: 2–4 hours  

---

### 2. Dynamic Integer Manager  
**What you build**:  
An interactive menu to:
- Allocate an `int` on the heap (`malloc`/`free` or `new`/`delete`)  
- Modify its value  
- Safely `free` it  
- Print address + current value  

**Must include**:  
- Dangling pointer prevention  
- Explicit memory cleanup  

**Key concepts**:  
- Heap vs stack  
- Object lifetime  
- Memory leaks  

**Time**: 1 day  

---

### 3. Custom Swap Functions  
**What you build**:  
Three swap implementations:
- Swap two integer **values**  
- Swap two **pointers**  
- Swap the **values pointed to** by two pointers  

**Key concepts**:  
- Pass-by-value vs pass-by-pointer  
- Function parameter semantics  
- Pointer manipulation  

**Time**: ½ day  

---

## Tier 2 — Memory Control *(Medium | Days 5–10)*  
**Goal**: You start controlling memory like a pro.

### 4. Dynamic Array Library  
**What you build**:  
A raw memory-based dynamic array with:
- `create_array(size)`  
- `resize_array(new_size)`  
- `destroy_array()`  

**Must include**:  
- Manual memory copying (`memcpy` or loop)  
- Re-allocation logic (even in C++)  

**Key concepts**:  
- Contiguous memory  
- Cost of resizing  
- Off-by-one errors  

**Time**: 1–2 days  

---

### 5. String Library *(No `std::string`!)*  
**What you build**:  
Your own C-style string utilities:
- `my_strlen()`  
- `my_strdup()`  
- `my_strcat()`  
- `my_strcmp()`  

**Must include**:  
- Null terminator (`\0`) handling  
- Heap allocation (`malloc`)  

**Key concepts**:  
- Why C strings are error-prone  
- Buffer overflows  
- Manual memory ownership  

**Time**: 1 day  

---

### 6. Linked List from Hell  
**What you build**:  
A robust singly linked list with:
- `add()`, `remove()`, `search()`  
- Safe full-list deallocation  

**Must include**:  
- Custom `struct` node  
- Pointers-to-pointers for safe removal  
- Memory leak prevention  

**Key concepts**:  
- Heap-based data graphs  
- Traversal patterns  
- Memory ownership semantics  

**Time**: 1–2 days  

---




