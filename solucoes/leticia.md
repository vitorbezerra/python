Respostas Leticia LISTA 1
 {


 "cells": [
  {
   "cell_type": "code",
   "execution_count": 1,
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
    "a=1+2\n",
    "print(a)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 4,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "2 5\n"
     ]
    }
   ],
   "source": [
    "x = 4\n",
    "y = x + 1\n",
    "x = 2\n",
    "print (x, y)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 8,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "hello worldhello worldhello worldhello world\n"
     ]
    }
   ],
   "source": [
    "str='hello world'\n",
    "strmult=str*4\n",
    "print(strmult)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 9,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "6 4\n"
     ]
    }
   ],
   "source": [
    "x, y = 2, 6\n",
    "x, y = y, x + 2\n",
    "print (x, y)\n"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 10,
   "metadata": {},
   "outputs": [
    {
     "ename": "NameError",
     "evalue": "name 'c' is not defined",
     "output_type": "error",
     "traceback": [
      "\u001b[0;31m---------------------------------------------------------------------------\u001b[0m",
      "\u001b[0;31mNameError\u001b[0m                                 Traceback (most recent call last)",
      "\u001b[0;32m<ipython-input-10-23218b6a3d9e>\u001b[0m in \u001b[0;36m<module>\u001b[0;34m\u001b[0m\n\u001b[1;32m      1\u001b[0m \u001b[0ma\u001b[0m\u001b[0;34m,\u001b[0m \u001b[0mb\u001b[0m \u001b[0;34m=\u001b[0m \u001b[0;36m2\u001b[0m\u001b[0;34m,\u001b[0m \u001b[0;36m3\u001b[0m\u001b[0;34m\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n\u001b[0;32m----> 2\u001b[0;31m \u001b[0mc\u001b[0m\u001b[0;34m,\u001b[0m \u001b[0mb\u001b[0m \u001b[0;34m=\u001b[0m \u001b[0ma\u001b[0m\u001b[0;34m,\u001b[0m \u001b[0mc\u001b[0m \u001b[0;34m+\u001b[0m \u001b[0;36m1\u001b[0m\u001b[0;34m\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n\u001b[0m\u001b[1;32m      3\u001b[0m \u001b[0mprint\u001b[0m \u001b[0;34m(\u001b[0m\u001b[0ma\u001b[0m\u001b[0;34m,\u001b[0m \u001b[0mb\u001b[0m\u001b[0;34m,\u001b[0m \u001b[0mc\u001b[0m\u001b[0;34m)\u001b[0m\u001b[0;34m\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n",
      "\u001b[0;31mNameError\u001b[0m: name 'c' is not defined"
     ]
    }
   ],
   "source": [
    "a, b = 2, 3\n",
    "c, b = a, c + 1\n",
    "print (a, b, c)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 12,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "25\n",
      "100\n"
     ]
    }
   ],
   "source": [
    "numcalls = 0\n",
    "def square(x):\n",
    "    global numcalls\n",
    "    numcalls = numcalls + 1\n",
    "    return x * x\n",
    "\n",
    "print (square(5))\n",
    "print (square(2*5))"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 40,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "1\n",
      "1\n"
     ]
    }
   ],
   "source": [
    "x = 1\n",
    "def f():\n",
    "    return x\n",
    "print (x)\n",
    "print (f())\n"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 16,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "3"
      ]
     },
     "execution_count": 16,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "1+2"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 18,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "1\n",
      "2\n",
      "1\n"
     ]
    }
   ],
   "source": [
    "x = 1\n",
    "def f():\n",
    "        x = 2\n",
    "        return x\n",
    "print (x)\n",
    "print (f())\n",
    "print (x)\n"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 27,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "1\n",
      "3\n",
      "1\n"
     ]
    }
   ],
   "source": [
    "x = 1\n",
    "def f():\n",
    "    x=1\n",
    "    y = x\n",
    "    x = 2\n",
    "    return x + y\n",
    "print (x)\n",
    "print (f())\n",
    "print (x)\n"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 23,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "2 9\n"
     ]
    }
   ],
   "source": [
    "x = 2\n",
    "def f(a):\n",
    "    x = a * a\n",
    "    return x\n",
    "y = f(3)\n",
    "print (x, y)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 62,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "12345\n",
      "1234.5\n",
      "123.45\n",
      "12.345\n",
      "5\n"
     ]
    }
   ],
   "source": [
    "def count_digits(resultado):\n",
    "    global cont \n",
    "    cont = 1\n",
    "    while resultado>10 :\n",
    "        print(resultado)\n",
    "        resultado=resultado/10\n",
    "        cont=cont+1\n",
    "    return cont\n",
    "\n",
    "#count_digits(5)\n",
    "count_digits(12345)\n",
    "\n",
    "print(cont)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 77,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "nao\n"
     ]
    }
   ],
   "source": [
    "### OPCAO 1\n",
    "\n",
    "import re \n",
    "\n",
    "\n",
    "txt = \"Python\"\n",
    "a=re.search(\"python\", txt)\n",
    "\n",
    "if (a):\n",
    "      print('sim')\n",
    "else:\n",
    "      print('nao')\n",
    "\n"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 81,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "True\n"
     ]
    }
   ],
   "source": [
    "### OPCAO 2\n",
    "\n",
    "a='Python'\n",
    "b='python'\n",
    "c=a.lower()\n",
    "d=b.lower()\n",
    "\n",
    "if c in d:\n",
    "    print (True)\n",
    "else:\n",
    "    print (False)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 34,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "True\n",
      "True\n",
      "True\n",
      "False\n"
     ]
    }
   ],
   "source": [
    "print(2 < 3 and 3 > 1)\n",
    "print (2 < 3 or 3 > 1)\n",
    "print (2 < 3 or not 3 > 1)\n",
    "print (2 < 3 and not 3 > 1)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 36,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "True\n"
     ]
    }
    {],
   "source": [
    "x = 4\n",
    "y = 5\n",
    "p = x < y or x < z\n",
    "print (p)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 38,
   "metadata": {},
   "outputs": [
    {
     "ename": "SyntaxError",
     "evalue": "can't assign to keyword (<ipython-input-38-3a825c604949>, line 1)",
     "output_type": "error",
     "traceback": [
      "\u001b[0;36m  File \u001b[0;32m\"<ipython-input-38-3a825c604949>\"\u001b[0;36m, line \u001b[0;32m1\u001b[0m\n\u001b[0;31m    True, False = False, True\u001b[0m\n\u001b[0m                             ^\u001b[0m\n\u001b[0;31mSyntaxError\u001b[0m\u001b[0;31m:\u001b[0m can't assign to keyword\n"
     ]
    }
   ],
   "source": [
    "True, False = False, True\n",
    "print (True, False)\n",
    "print (2 < 3)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 39,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "2\n"
     ]
    }
   ],
   "source": [
    "x = 2\n",
    "if x == 2:\n",
    "    print(x)\n",
  {   "else:\n",
    "    print(y)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 86,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "2\n"
     ]
    }
   ],
   "source": [
    "x = 2\n",
    "if x == 2:\n",
    "     print(x)\n",
    "else:\n",
    "     x+=1"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {},
   "outputs": [],
   "source": []
  }
 ],
 "metadata": {
  "kernelspec": {
   "display_name": "Python [conda env:ambi] *",
   "language": "python",
   "name": "conda-env-ambi-py"
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
   "version": "3.7.4"
  }
 },
 "nbformat": 4,
 "nbformat_minor": 2
}
