# PythonExample[Python_notebook.ipynb](https://github.com/user-attachments/files/26054748/Python_notebook.ipynb)
{
 "cells": [
  {
   "cell_type": "markdown",
   "id": "ca98a8f2",
   "metadata": {},
   "source": [
    "## Python02_DataType"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 92,
   "id": "6af949b0",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "<class 'float'>\n",
      "<class 'float'>\n",
      "<class 'float'>\n"
     ]
    }
   ],
   "source": [
    "x = 1.10\n",
    "y = 1.0\n",
    "z = -35.59\n",
    "print(type(x))\n",
    "print(type(y))\n",
    "print(type(z))"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 93,
   "id": "c14fe350",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "4\n",
      "1\n"
     ]
    }
   ],
   "source": [
    "import random\n",
    "print(random.randrange(1, 10))\n",
    "print(random.randrange(1, 10))"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 94,
   "id": "121a95ee",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "Lorem ipsum dolor sit amet,\n",
      "consectetur adipiscing elit,\n",
      "sed do eiusmod tempor incididunt\n",
      "ut labore et dolore magna aliqua.\n"
     ]
    }
   ],
   "source": [
    "a = \"\"\"Lorem ipsum dolor sit amet,\n",
    "consectetur adipiscing elit,\n",
    "sed do eiusmod tempor incididunt\n",
    "ut labore et dolore magna aliqua.\"\"\"\n",
    "print(a)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 95,
   "id": "9328f697",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "llo\n",
      "Hello\n",
      "llo, World!\n"
     ]
    }
   ],
   "source": [
    "b = \"Hello, World!\"\n",
    "print(b[2:5])\n",
    "print(b[:5])\n",
    "print(b[2:])"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 96,
   "id": "2011c0f5",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "HELLO, WORLD!\n",
      "hello, world!\n"
     ]
    }
   ],
   "source": [
    "a = \"Hello, World!\"\n",
    "print(a.upper())\n",
    "print(a.lower())"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 97,
   "id": "95eae21a",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "My name is John, I am 36\n"
     ]
    }
   ],
   "source": [
    "age = 36\n",
    "txt = f\"My name is John, I am {age}\"\n",
    "print(txt)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 98,
   "id": "b3456ff3",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "b is not greater than a\n"
     ]
    }
   ],
   "source": [
    "a = 200\n",
    "b = 33\n",
    "if b > a:\n",
    "  print(\"b is greater than a\")\n",
    "else:\n",
    "  print(\"b is not greater than a\")"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 99,
   "id": "02c940a4",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "True\n",
      "True\n"
     ]
    }
   ],
   "source": [
    "x = \"Hello\"\n",
    "y = 15\n",
    "print(bool(x))\n",
    "print(bool(y))"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "id": "24585544",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "List has 5 elements\n"
     ]
    }
   ],
   "source": [
    "numbers = [1, 2, 3, 4, 5]\n",
    "if (count := len(numbers)) > 3:\n",
    "    print(f\"List has {count} elements\")"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 101,
   "id": "becab7d7",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "True\n",
      "True\n",
      "False\n"
     ]
    }
   ],
   "source": [
    "x = 5\n",
    "print(1 < x < 10)\n",
    "print(1 < x and x < 10)\n",
    "print(not(x > 3 and x < 10))"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 102,
   "id": "231607b4",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "True\n",
      "False\n",
      "True\n"
     ]
    }
   ],
   "source": [
    "text = \"Hello World\"\n",
    "print(\"H\" in text)\n",
    "print(\"hello\" in text)\n",
    "print(\"z\" not in text)"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "278bdb36",
   "metadata": {},
   "source": [
    "## Python03_ListTuple"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 1,
   "id": "b9c5b165",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "['apple', 'banana', 'cherry']\n"
     ]
    }
   ],
   "source": [
    "thislist = [\"apple\", \"banana\", \"cherry\"]\n",
    "print(thislist)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 2,
   "id": "9dd75238",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "3\n"
     ]
    }
   ],
   "source": [
    "thislist = [\"apple\", \"banana\", \"cherry\"]\n",
    "print(len(thislist))"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 6,
   "id": "b8c28ca4",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "<class 'list'>\n",
      "['apple', 'banana', 'cherry']\n",
      "<class 'list'>\n"
     ]
    }
   ],
   "source": [
    "mylist = [\"apple\", \"banana\", \"cherry\"]\n",
    "print(type(mylist))\n",
    "\n",
    "thislist = list((\"apple\", \"banana\", \"cherry\")) # note the double round-brackets\n",
    "print(thislist)\n",
    "print(type(thislist))"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 7,
   "id": "171ca38a",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "cherry\n"
     ]
    }
   ],
   "source": [
    "thislist = [\"apple\", \"banana\", \"cherry\"]\n",
    "print(thislist[-1])"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 8,
   "id": "abd3eda2",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "['cherry', 'orange', 'kiwi']\n",
      "['apple', 'banana', 'cherry', 'orange']\n",
      "['cherry', 'orange', 'kiwi', 'melon', 'mango']\n"
     ]
    }
   ],
   "source": [
    "thislist = [\"apple\", \"banana\", \"cherry\", \"orange\", \"kiwi\", \"melon\", \"mango\"]\n",
    "print(thislist[2:5])\n",
    "print(thislist[:4])\n",
    "print(thislist[2:])"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 9,
   "id": "b5f89b0e",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "['apple', 'blackcurrant', 'watermelon', 'orange', 'kiwi', 'mango']\n"
     ]
    }
   ],
   "source": [
    "thislist = [\"apple\", \"banana\", \"cherry\", \"orange\", \"kiwi\", \"mango\"]\n",
    "thislist[1:3] = [\"blackcurrant\", \"watermelon\"]\n",
    "print(thislist)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 11,
   "id": "2242721f",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "['apple', 'blackcurrant', 'watermelon', 'cherry']\n",
      "['apple', 'watermelon', 'cherry']\n"
     ]
    }
   ],
   "source": [
    "thislist = [\"apple\", \"banana\", \"cherry\"]\n",
    "thislist[1:2] = [\"blackcurrant\", \"watermelon\"]\n",
    "print(thislist)\n",
    "thislist[1:3] = [\"watermelon\"]\n",
    "print(thislist)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 12,
   "id": "95dc4033",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "['apple', 'banana', 'cherry', 'orange']\n"
     ]
    }
   ],
   "source": [
    "thislist = [\"apple\", \"banana\", \"cherry\"]\n",
    "thislist.append(\"orange\")\n",
    "print(thislist)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 13,
   "id": "097aa204",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "['apple', 'orange', 'banana', 'cherry']\n"
     ]
    }
   ],
   "source": [
    "thislist = [\"apple\", \"banana\", \"cherry\"]\n",
    "thislist.insert(1, \"orange\")\n",
    "print(thislist)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 14,
   "id": "e43bdec9",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "['apple', 'banana', 'cherry', 'mango', 'pineapple', 'papaya']\n"
     ]
    }
   ],
   "source": [
    "thislist = [\"apple\", \"banana\", \"cherry\"]\n",
    "tropical = [\"mango\", \"pineapple\", \"papaya\"]\n",
    "thislist.extend(tropical)\n",
    "print(thislist)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 15,
   "id": "44bb2337",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "['apple', 'banana', 'cherry', 'kiwi', 'orange']\n"
     ]
    }
   ],
   "source": [
    "thislist = [\"apple\", \"banana\", \"cherry\"]\n",
    "thistuple = (\"kiwi\", \"orange\")\n",
    "thislist.extend(thistuple)\n",
    "print(thislist)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 19,
   "id": "f0cd347b",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "['apple', 'cherry', 'banana', 'kiwi']\n",
      "['apple', 'banana']\n",
      "['banana', 'cherry']\n"
     ]
    }
   ],
   "source": [
    "thislist = [\"apple\", \"banana\", \"cherry\", \"banana\", \"kiwi\"]\n",
    "thislist.remove(\"banana\")\n",
    "print(thislist)\n",
    "\n",
    "thislist = [\"apple\", \"banana\", \"cherry\"]\n",
    "thislist.pop()\n",
    "print(thislist)\n",
    "\n",
    "thislist = [\"apple\", \"banana\", \"cherry\"]\n",
    "del thislist[0]\n",
    "print(thislist)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 20,
   "id": "b4ff4a9b",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "[]\n"
     ]
    }
   ],
   "source": [
    "thislist = [\"apple\", \"banana\", \"cherry\"]\n",
    "thislist.clear()\n",
    "print(thislist)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 22,
   "id": "177ad9e9",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "apple\n",
      "banana\n",
      "cherry\n"
     ]
    }
   ],
   "source": [
    "thislist = [\"apple\", \"banana\", \"cherry\"]\n",
    "for i in thislist:\n",
    "  print(i)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "id": "487f5864",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "apple\n",
      "0 apple\n",
      "banana\n",
      "1 banana\n",
      "cherry\n",
      "2 cherry\n"
     ]
    }
   ],
   "source": [
    "thislist = [\"apple\", \"banana\", \"cherry\"]\n",
    "for i in range(len(thislist)):\n",
    "  print(thislist[i])\n",
    "  print(i, thislist[i])"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 25,
   "id": "bc14444f",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "apple\n",
      "banana\n",
      "cherry\n"
     ]
    }
   ],
   "source": [
    "thislist = [\"apple\", \"banana\", \"cherry\"]\n",
    "i = 0\n",
    "while i < len(thislist):\n",
    "  print(thislist[i])\n",
    "  i = i + 1"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 33,
   "id": "8ee9d8bc",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "apple\n",
      "banana\n",
      "cherry\n"
     ]
    },
    {
     "data": {
      "text/plain": [
       "[None, None, None]"
      ]
     },
     "execution_count": 33,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "thislist = [\"apple\", \"banana\", \"cherry\"]\n",
    "[print(x) for x in thislist]"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 38,
   "id": "cc0651ea",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "['apple', 'banana', 'mango']\n"
     ]
    }
   ],
   "source": [
    "fruits = [\"apple\", \"banana\", \"cherry\", \"kiwi\", \"mango\"]\n",
    "newlist = [x for x in fruits if \"a\" in x]\n",
    "print(newlist)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 37,
   "id": "b5938789",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "['apple', 'banana', 'mango']\n"
     ]
    }
   ],
   "source": [
    "fruits = [\"apple\", \"banana\", \"cherry\", \"kiwi\", \"mango\"]\n",
    "newlist = []\n",
    "for x in fruits:\n",
    "  if \"a\" in x:\n",
    "    newlist.append(x)\n",
    "print(newlist)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 40,
   "id": "74d31420",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "[0, 1, 2, 3, 4, 5, 6, 7, 8, 9]\n",
      "[0, 1, 2, 3, 4]\n"
     ]
    }
   ],
   "source": [
    "newlist = [x for x in range(10)]\n",
    "print(newlist)\n",
    "newlist = [x for x in range(10) if x < 5]\n",
    "print(newlist)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 43,
   "id": "2a6d7a1a",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "['APPLE', 'BANANA', 'CHERRY', 'KIWI', 'MANGO']\n",
      "['hello', 'hello', 'hello', 'hello', 'hello']\n"
     ]
    }
   ],
   "source": [
    "newlist = [x.upper() for x in fruits]\n",
    "print(newlist)\n",
    "newlist = ['hello' for x in fruits]\n",
    "print(newlist)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 44,
   "id": "b98fadf2",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "['apple', 'orange', 'cherry', 'kiwi', 'mango']\n"
     ]
    }
   ],
   "source": [
    "fruits = [\"apple\", \"banana\", \"cherry\", \"kiwi\", \"mango\"]\n",
    "newlist = [x if x != \"banana\" else \"orange\" for x in fruits]\n",
    "print(newlist)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 47,
   "id": "20c5792e",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "['apple', 'banana', 'cherry', 'kiwi', 'mango']\n"
     ]
    }
   ],
   "source": [
    "fruits = [\"apple\", \"banana\", \"cherry\", \"kiwi\", \"mango\"]\n",
    "newlist = [x for x in fruits]\n",
    "print(newlist)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 48,
   "id": "c93a4364",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "['banana', 'kiwi', 'mango', 'orange', 'pineapple']\n"
     ]
    }
   ],
   "source": [
    "thislist = [\"orange\", \"mango\", \"kiwi\", \"pineapple\", \"banana\"]\n",
    "thislist.sort()\n",
    "print(thislist)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 49,
   "id": "4b4a783e",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "[23, 50, 65, 82, 100]\n"
     ]
    }
   ],
   "source": [
    "thislist = [100, 50, 65, 82, 23]\n",
    "thislist.sort()\n",
    "print(thislist)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 52,
   "id": "dc126335",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "['apple', 'banana', 'cherry']\n"
     ]
    }
   ],
   "source": [
    "thislist = [\"apple\", \"banana\", \"cherry\"]\n",
    "mylist = thislist.copy()\n",
    "print(mylist)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 58,
   "id": "35c866be",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "['apple', 'banana', 'cherry']\n",
      "['apple', 'banana', 'cherry']\n"
     ]
    }
   ],
   "source": [
    "thislist = [\"apple\", \"banana\", \"cherry\"]\n",
    "mylist = list(thislist)\n",
    "print(mylist)\n",
    "\n",
    "thislist[0]=\"pink\"\n",
    "print(mylist)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 56,
   "id": "a5556a81",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "['apple', 'banana', 'cherry']\n",
      "['apple', 'banana', 'cherry']\n",
      "['pink', 'banana', 'cherry']\n"
     ]
    }
   ],
   "source": [
    "thislist = [\"apple\", \"banana\", \"cherry\"]\n",
    "mylist = thislist.copy()\n",
    "print(mylist)\n",
    "\n",
    "thislist[0]=\"pink\"\n",
    "print(mylist)\n",
    "print(thislist)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 60,
   "id": "d9db5670",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "['a', 'b', 'c', 1, 2, 3]\n"
     ]
    }
   ],
   "source": [
    "list1 = [\"a\", \"b\", \"c\"]\n",
    "list2 = [1, 2, 3]\n",
    "for x in list2:\n",
    "  list1.append(x)\n",
    "print(list1)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 61,
   "id": "7239d632",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "('apple', 'kiwi', 'cherry')\n"
     ]
    }
   ],
   "source": [
    "x = (\"apple\", \"banana\", \"cherry\")\n",
    "y = list(x)\n",
    "y[1] = \"kiwi\"\n",
    "x = tuple(y)\n",
    "print(x)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 63,
   "id": "79ad21b6",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "('apple', 'banana', 'cherry', 'orange')\n"
     ]
    }
   ],
   "source": [
    "thistuple = (\"apple\", \"banana\", \"cherry\")\n",
    "y = list(thistuple)\n",
    "y.append(\"orange\")\n",
    "thistuple = tuple(y)\n",
    "print(thistuple)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 64,
   "id": "87f80cbe",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "('apple', 'banana', 'cherry', 'orange')\n"
     ]
    }
   ],
   "source": [
    "thistuple = (\"apple\", \"banana\", \"cherry\")\n",
    "y = (\"orange\",)\n",
    "thistuple += y\n",
    "print(thistuple)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 65,
   "id": "b8b90097",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "apple\n",
      "banana\n",
      "cherry\n"
     ]
    }
   ],
   "source": [
    "fruits = (\"apple\", \"banana\", \"cherry\")\n",
    "(green, yellow, red) = fruits\n",
    "print(green)\n",
    "print(yellow)\n",
    "print(red)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 67,
   "id": "63accb2a",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "apple\n",
      "banana\n",
      "cherry\n"
     ]
    }
   ],
   "source": [
    "thistuple = (\"apple\", \"banana\", \"cherry\")\n",
    "for x in thistuple:\n",
    "  print(x)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 70,
   "id": "ceaba0ba",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "('apple', 'banana', 'cherry', 'apple', 'banana', 'cherry')\n"
     ]
    }
   ],
   "source": [
    "fruits = (\"apple\", \"banana\", \"cherry\")\n",
    "mytuple = fruits * 2\n",
    "print(mytuple)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 71,
   "id": "2a623fba",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "{'apple', 'cherry', 'banana'}\n"
     ]
    }
   ],
   "source": [
    "thisset = {\"apple\", \"banana\", \"cherry\", \"apple\"}\n",
    "print(thisset)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 72,
   "id": "29eb3aa4",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "{True, 2, 'cherry', 'apple', 'banana'}\n"
     ]
    }
   ],
   "source": [
    "thisset = {\"apple\", \"banana\", \"cherry\", True, 1, 2}\n",
    "print(thisset)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 86,
   "id": "09393202",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "{False, True, 'cherry', 'apple', 'banana'}\n"
     ]
    }
   ],
   "source": [
    "thisset = {\"apple\", \"banana\", \"cherry\", False, True, 0}\n",
    "print(thisset)"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "d44fefb5",
   "metadata": {},
   "source": [
    "## Python03_Dictionary"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 87,
   "id": "2ee2e8d3",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "{'brand': 'Ford', 'model': 'Mustang', 'year': 1964}\n",
      "1964\n"
     ]
    }
   ],
   "source": [
    "thisdict = {\n",
    "\"brand\": \"Ford\",\n",
    "\"model\": \"Mustang\",\n",
    "\"year\": 1964\n",
    "}\n",
    "print(thisdict)\n",
    "print(thisdict[\"year\"])"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 88,
   "id": "d17df508",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "3\n"
     ]
    }
   ],
   "source": [
    "print(len(thisdict))"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 89,
   "id": "1bc9d858",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "{'brand': 'Ford', 'model': 'Mustang', 'year': 2020}\n"
     ]
    }
   ],
   "source": [
    "thisdict = {\n",
    "  \"brand\": \"Ford\",\n",
    "  \"model\": \"Mustang\",\n",
    "  \"year\": 1964,\n",
    "  \"year\": 2020\n",
    "}\n",
    "print(thisdict)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 90,
   "id": "7c5bcb2e",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "{'brand': 'Ford', 'electric': False, 'year': 1964, 'colors': ['red', 'white', 'blue']}\n"
     ]
    }
   ],
   "source": [
    "thisdict = {\n",
    "\"brand\": \"Ford\",\n",
    "\"electric\": False,\n",
    "\"year\": 1964,\n",
    "\"colors\": [\"red\", \"white\", \"blue\"]\n",
    "}\n",
    "print(thisdict)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 91,
   "id": "86d05cda",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "{'name': 'John', 'age': 36, 'country': 'Norway'}\n"
     ]
    }
   ],
   "source": [
    "thisdict = dict(name = \"John\", age = 36, country = \"Norway\")\n",
    "print(thisdict)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 4,
   "id": "62bec6a8",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "dict_keys(['brand', 'model', 'year'])\n",
      "dict_keys(['brand', 'model', 'year', 'color'])\n"
     ]
    }
   ],
   "source": [
    "car = {\n",
    "  \"brand\": \"Ford\",\n",
    "  \"model\": \"Mustang\",\n",
    "  \"year\": 1964\n",
    "}\n",
    "x = car.keys()\n",
    "print(x)\n",
    "car[\"color\"] = \"white\"\n",
    "print(x)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 3,
   "id": "2c1a4095",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "{'brand': 'Ford', 'model': 'Mustang', 'year': 1964, 'color': 'white'}\n"
     ]
    }
   ],
   "source": [
    "print(car)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 5,
   "id": "12bdedb6",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "dict_values(['Ford', 'Mustang', 1964])\n",
      "dict_values(['Ford', 'Mustang', 2020])\n"
     ]
    }
   ],
   "source": [
    "car = {\n",
    "  \"brand\": \"Ford\",\n",
    "  \"model\": \"Mustang\",\n",
    "  \"year\": 1964\n",
    "}\n",
    "x = car.values()\n",
    "print(x)\n",
    "car[\"year\"] = 2020\n",
    "print(x)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 6,
   "id": "476cbc71",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "dict_values(['Ford', 'Mustang', 1964])\n",
      "dict_values(['Ford', 'Mustang', 1964, 'red'])\n"
     ]
    }
   ],
   "source": [
    "car = {\n",
    "  \"brand\": \"Ford\",\n",
    "  \"model\": \"Mustang\",\n",
    "  \"year\": 1964\n",
    "}\n",
    "x = car.values()\n",
    "print(x) #before the change\n",
    "car[\"color\"] = \"red\"\n",
    "print(x)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 8,
   "id": "a65d1a72",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "Yes, 'model' is one of the keys in the thisdict dictionary\n"
     ]
    }
   ],
   "source": [
    "thisdict = {\n",
    "  \"brand\": \"Ford\",\n",
    "  \"model\": \"Mustang\",\n",
    "  \"year\": 1964\n",
    "}\n",
    "if \"model\" in thisdict:\n",
    "  print(\"Yes, 'model' is one of the keys in the thisdict dictionary\")"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 9,
   "id": "2bc0e6c1",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "{'brand': 'Ford', 'model': 'Mustang', 'year': 1964, 'color': 'red'}\n"
     ]
    }
   ],
   "source": [
    "thisdict = {\n",
    "  \"brand\": \"Ford\",\n",
    "  \"model\": \"Mustang\",\n",
    "  \"year\": 1964\n",
    "}\n",
    "thisdict.update({\"color\": \"red\"})\n",
    "print(thisdict)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 10,
   "id": "b0c6718a",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "{'brand': 'Ford', 'year': 1964}\n"
     ]
    }
   ],
   "source": [
    "thisdict = {\n",
    "\"brand\": \"Ford\",\n",
    "\"model\": \"Mustang\",\n",
    "\"year\": 1964\n",
    "}\n",
    "del thisdict[\"model\"]\n",
    "print(thisdict)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 12,
   "id": "9eccd384",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "{}\n"
     ]
    }
   ],
   "source": [
    "thisdict = {\n",
    "  \"brand\": \"Ford\",\n",
    "  \"model\": \"Mustang\",\n",
    "  \"year\": 1964\n",
    "}\n",
    "thisdict.clear()\n",
    "print(thisdict)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 17,
   "id": "6e716224",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "brand\n",
      "model\n",
      "year\n",
      "Ford\n",
      "Mustang\n",
      "1964\n",
      "brand Ford\n",
      "model Mustang\n",
      "year 1964\n"
     ]
    }
   ],
   "source": [
    "thisdict = {\n",
    "  \"brand\": \"Ford\",\n",
    "  \"model\": \"Mustang\",\n",
    "  \"year\": 1964\n",
    "}\n",
    "for x in thisdict:\n",
    "  print(x)\n",
    "\n",
    "for x in thisdict:\n",
    "  print(thisdict[x])  \n",
    "\n",
    "for x,y in thisdict.items():\n",
    "  print(x, y)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 18,
   "id": "bb783cfd",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "{'brand': 'Ford', 'model': 'Mustang', 'year': 1964}\n"
     ]
    }
   ],
   "source": [
    "thisdict = {\n",
    "  \"brand\": \"Ford\",\n",
    "  \"model\": \"Mustang\",\n",
    "  \"year\": 1964\n",
    "}\n",
    "mydict = thisdict.copy()\n",
    "print(mydict)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 21,
   "id": "93f88951",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "{'child1': {'name': 'Emil', 'year': 2004}, 'child2': {'name': 'Tobias', 'year': 2007}, 'child3': {'name': 'Linus', 'year': 2011}}\n",
      "{'name': 'Emil', 'year': 2004}\n"
     ]
    }
   ],
   "source": [
    "myfamily = {\n",
    "\"child1\" : {\n",
    "\"name\" : \"Emil\",\n",
    "\"year\" : 2004\n",
    "  },\n",
    "\"child2\" : {\n",
    "\"name\" : \"Tobias\",\n",
    "\"year\" : 2007\n",
    "  },\n",
    "\"child3\" : {\n",
    "\"name\" : \"Linus\",\n",
    "\"year\" : 2011\n",
    "  }\n",
    "}\n",
    "print(myfamily)\n",
    "print(myfamily[\"child1\"])"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 24,
   "id": "bc4884e3",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "child1\n",
      "child2\n",
      "child3\n",
      "name: Linus\n",
      "year: 2011\n"
     ]
    }
   ],
   "source": [
    "for x, obj in myfamily.items():\n",
    "  print(x)\n",
    "for y in obj:\n",
    "  print(y + ':', obj[y])"
   ]
  }
 ],
 "metadata": {
  "kernelspec": {
   "display_name": "Python 3",
   "language": "python",
   "name": "python3"
  },
  "language_info": {
   "codemirror_mode": {
    "name": "ipython",
    "version": 3
   },
   "file_extension": ".py",
   "mimetype": "text/x-python",
   "name": "python",
   "nbconvert_exporter": "python",
   "pygments_lexer": "ipython3",
   "version": "3.14.2"
  }
 },
 "nbformat": 4,
 "nbformat_minor": 5
}
