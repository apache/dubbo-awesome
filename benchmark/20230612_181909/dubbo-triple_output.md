# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.592 ops/ms
# Warmup Iteration   2: 3.393 ops/ms
# Warmup Iteration   3: 7.079 ops/ms
Iteration   1: 7.001 ops/ms
Iteration   2: 7.795 ops/ms
Iteration   3: 7.791 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.529 ±(99.9%) 8.342 ops/ms [Average]
  (min, avg, max) = (7.001, 7.529, 7.795), stdev = 0.457
  CI (99.9%): [≈ 0, 15.871] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:13
# Fork: 1 of 1
# Warmup Iteration   1: 2.280 ops/ms
# Warmup Iteration   2: 6.258 ops/ms
# Warmup Iteration   3: 7.973 ops/ms
Iteration   1: 7.679 ops/ms
Iteration   2: 8.351 ops/ms
Iteration   3: 7.958 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  7.996 ±(99.9%) 6.158 ops/ms [Average]
  (min, avg, max) = (7.679, 7.996, 8.351), stdev = 0.338
  CI (99.9%): [1.839, 14.154] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:05
# Fork: 1 of 1
# Warmup Iteration   1: 2.026 ops/ms
# Warmup Iteration   2: 6.222 ops/ms
# Warmup Iteration   3: 7.378 ops/ms
Iteration   1: 8.139 ops/ms
Iteration   2: 8.180 ops/ms
Iteration   3: 7.840 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.053 ±(99.9%) 3.379 ops/ms [Average]
  (min, avg, max) = (7.840, 8.053, 8.180), stdev = 0.185
  CI (99.9%): [4.674, 11.432] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:58
# Fork: 1 of 1
# Warmup Iteration   1: 2.029 ops/ms
# Warmup Iteration   2: 4.940 ops/ms
# Warmup Iteration   3: 6.224 ops/ms
Iteration   1: 6.340 ops/ms
Iteration   2: 6.623 ops/ms
Iteration   3: 6.687 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.550 ±(99.9%) 3.362 ops/ms [Average]
  (min, avg, max) = (6.340, 6.550, 6.687), stdev = 0.184
  CI (99.9%): [3.188, 9.912] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:52
# Fork: 1 of 1
# Warmup Iteration   1: 14.034 ±(99.9%) 0.070 ms/op
# Warmup Iteration   2: 4.701 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.226 ±(99.9%) 0.009 ms/op
Iteration   1: 4.135 ±(99.9%) 0.008 ms/op
Iteration   2: 3.908 ±(99.9%) 0.005 ms/op
Iteration   3: 3.943 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.995 ±(99.9%) 2.226 ms/op [Average]
  (min, avg, max) = (3.908, 3.995, 4.135), stdev = 0.122
  CI (99.9%): [1.770, 6.221] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:45
# Fork: 1 of 1
# Warmup Iteration   1: 11.711 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 4.484 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.141 ±(99.9%) 0.005 ms/op
Iteration   1: 3.938 ±(99.9%) 0.005 ms/op
Iteration   2: 3.800 ±(99.9%) 0.007 ms/op
Iteration   3: 3.897 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.879 ±(99.9%) 1.293 ms/op [Average]
  (min, avg, max) = (3.800, 3.879, 3.938), stdev = 0.071
  CI (99.9%): [2.585, 5.172] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:38
# Fork: 1 of 1
# Warmup Iteration   1: 13.206 ±(99.9%) 0.080 ms/op
# Warmup Iteration   2: 4.924 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.442 ±(99.9%) 0.006 ms/op
Iteration   1: 4.149 ±(99.9%) 0.007 ms/op
Iteration   2: 4.092 ±(99.9%) 0.005 ms/op
Iteration   3: 4.212 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.151 ±(99.9%) 1.094 ms/op [Average]
  (min, avg, max) = (4.092, 4.151, 4.212), stdev = 0.060
  CI (99.9%): [3.058, 5.245] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 16.214 ±(99.9%) 0.070 ms/op
# Warmup Iteration   2: 6.283 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 5.003 ±(99.9%) 0.010 ms/op
Iteration   1: 4.835 ±(99.9%) 0.010 ms/op
Iteration   2: 4.730 ±(99.9%) 0.010 ms/op
Iteration   3: 4.602 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.722 ±(99.9%) 2.126 ms/op [Average]
  (min, avg, max) = (4.602, 4.722, 4.835), stdev = 0.117
  CI (99.9%): [2.596, 6.849] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 12.310 ±(99.9%) 0.190 ms/op
# Warmup Iteration   2: 5.183 ±(99.9%) 0.033 ms/op
# Warmup Iteration   3: 4.520 ±(99.9%) 0.019 ms/op
Iteration   1: 4.381 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   1.882 ms/op
                 createUser·p0.50:   4.043 ms/op
                 createUser·p0.90:   5.571 ms/op
                 createUser·p0.95:   6.791 ms/op
                 createUser·p0.99:   9.617 ms/op
                 createUser·p0.999:  13.828 ms/op
                 createUser·p0.9999: 26.476 ms/op
                 createUser·p1.00:   27.820 ms/op

Iteration   2: 4.154 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.849 ms/op
                 createUser·p0.50:   3.957 ms/op
                 createUser·p0.90:   4.841 ms/op
                 createUser·p0.95:   5.456 ms/op
                 createUser·p0.99:   7.963 ms/op
                 createUser·p0.999:  26.637 ms/op
                 createUser·p0.9999: 28.560 ms/op
                 createUser·p1.00:   29.557 ms/op

Iteration   3: 3.966 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.690 ms/op
                 createUser·p0.50:   3.834 ms/op
                 createUser·p0.90:   4.432 ms/op
                 createUser·p0.95:   4.710 ms/op
                 createUser·p0.99:   6.627 ms/op
                 createUser·p0.999:  28.715 ms/op
                 createUser·p0.9999: 31.949 ms/op
                 createUser·p1.00:   33.391 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 230802
  mean =      4.160 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 415 
    [ 2.500,  5.000) = 211755 
    [ 5.000,  7.500) = 14879 
    [ 7.500, 10.000) = 2669 
    [10.000, 12.500) = 673 
    [12.500, 15.000) = 88 
    [15.000, 17.500) = 36 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 52 
    [25.000, 27.500) = 80 
    [27.500, 30.000) = 76 
    [30.000, 32.500) = 52 
    [32.500, 35.000) = 5 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.690 ms/op
     p(50.0000) =      3.924 ms/op
     p(90.0000) =      4.833 ms/op
     p(95.0000) =      5.652 ms/op
     p(99.0000) =      8.389 ms/op
     p(99.9000) =     24.451 ms/op
     p(99.9900) =     31.127 ms/op
     p(99.9990) =     33.262 ms/op
     p(99.9999) =     33.391 ms/op
    p(100.0000) =     33.391 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 11.581 ±(99.9%) 0.176 ms/op
# Warmup Iteration   2: 4.859 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 4.059 ±(99.9%) 0.012 ms/op
Iteration   1: 3.914 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.753 ms/op
                 existUser·p0.50:   3.682 ms/op
                 existUser·p0.90:   4.661 ms/op
                 existUser·p0.95:   5.325 ms/op
                 existUser·p0.99:   7.376 ms/op
                 existUser·p0.999:  10.732 ms/op
                 existUser·p0.9999: 27.398 ms/op
                 existUser·p1.00:   27.984 ms/op

Iteration   2: 3.919 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.849 ms/op
                 existUser·p0.50:   3.768 ms/op
                 existUser·p0.90:   4.547 ms/op
                 existUser·p0.95:   4.989 ms/op
                 existUser·p0.99:   6.783 ms/op
                 existUser·p0.999:  25.254 ms/op
                 existUser·p0.9999: 28.830 ms/op
                 existUser·p1.00:   30.147 ms/op

Iteration   3: 4.000 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.935 ms/op
                 existUser·p0.50:   3.772 ms/op
                 existUser·p0.90:   4.678 ms/op
                 existUser·p0.95:   5.603 ms/op
                 existUser·p0.99:   7.987 ms/op
                 existUser·p0.999:  15.696 ms/op
                 existUser·p0.9999: 33.325 ms/op
                 existUser·p1.00:   34.537 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 243351
  mean =      3.944 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 430 
    [ 2.500,  5.000) = 227490 
    [ 5.000,  7.500) = 13058 
    [ 7.500, 10.000) = 1693 
    [10.000, 12.500) = 375 
    [12.500, 15.000) = 63 
    [15.000, 17.500) = 16 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 41 
    [25.000, 27.500) = 87 
    [27.500, 30.000) = 43 
    [30.000, 32.500) = 33 
    [32.500, 35.000) = 19 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.753 ms/op
     p(50.0000) =      3.740 ms/op
     p(90.0000) =      4.620 ms/op
     p(95.0000) =      5.292 ms/op
     p(99.0000) =      7.471 ms/op
     p(99.9000) =     14.773 ms/op
     p(99.9900) =     32.102 ms/op
     p(99.9990) =     34.350 ms/op
     p(99.9999) =     34.537 ms/op
    p(100.0000) =     34.537 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 12.595 ±(99.9%) 0.157 ms/op
# Warmup Iteration   2: 5.121 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 4.084 ±(99.9%) 0.014 ms/op
Iteration   1: 4.111 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   0.648 ms/op
                 getUser·p0.50:   3.854 ms/op
                 getUser·p0.90:   4.874 ms/op
                 getUser·p0.95:   6.177 ms/op
                 getUser·p0.99:   9.290 ms/op
                 getUser·p0.999:  24.510 ms/op
                 getUser·p0.9999: 38.470 ms/op
                 getUser·p1.00:   39.125 ms/op

Iteration   2: 3.965 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.970 ms/op
                 getUser·p0.50:   3.777 ms/op
                 getUser·p0.90:   4.612 ms/op
                 getUser·p0.95:   5.267 ms/op
                 getUser·p0.99:   7.313 ms/op
                 getUser·p0.999:  16.734 ms/op
                 getUser·p0.9999: 27.851 ms/op
                 getUser·p1.00:   29.884 ms/op

Iteration   3: 4.023 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.587 ms/op
                 getUser·p0.50:   3.838 ms/op
                 getUser·p0.90:   4.669 ms/op
                 getUser·p0.95:   5.505 ms/op
                 getUser·p0.99:   7.774 ms/op
                 getUser·p0.999:  14.645 ms/op
                 getUser·p0.9999: 33.195 ms/op
                 getUser·p1.00:   34.406 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 237988
  mean =      4.033 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 163 
    [ 2.500,  5.000) = 220251 
    [ 5.000,  7.500) = 14109 
    [ 7.500, 10.000) = 2580 
    [10.000, 12.500) = 462 
    [12.500, 15.000) = 137 
    [15.000, 17.500) = 27 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 38 
    [25.000, 27.500) = 73 
    [27.500, 30.000) = 50 
    [30.000, 32.500) = 13 
    [32.500, 35.000) = 31 
    [35.000, 37.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.648 ms/op
     p(50.0000) =      3.826 ms/op
     p(90.0000) =      4.710 ms/op
     p(95.0000) =      5.612 ms/op
     p(99.0000) =      7.987 ms/op
     p(99.9000) =     19.728 ms/op
     p(99.9900) =     34.813 ms/op
     p(99.9990) =     39.010 ms/op
     p(99.9999) =     39.125 ms/op
    p(100.0000) =     39.125 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 16.076 ±(99.9%) 0.250 ms/op
# Warmup Iteration   2: 6.160 ±(99.9%) 0.037 ms/op
# Warmup Iteration   3: 4.907 ±(99.9%) 0.017 ms/op
Iteration   1: 4.910 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   2.617 ms/op
                 listUser·p0.50:   4.710 ms/op
                 listUser·p0.90:   5.366 ms/op
                 listUser·p0.95:   6.619 ms/op
                 listUser·p0.99:   9.339 ms/op
                 listUser·p0.999:  24.379 ms/op
                 listUser·p0.9999: 27.312 ms/op
                 listUser·p1.00:   31.785 ms/op

Iteration   2: 4.865 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   2.183 ms/op
                 listUser·p0.50:   4.538 ms/op
                 listUser·p0.90:   5.560 ms/op
                 listUser·p0.95:   6.980 ms/op
                 listUser·p0.99:   9.945 ms/op
                 listUser·p0.999:  18.053 ms/op
                 listUser·p0.9999: 27.656 ms/op
                 listUser·p1.00:   28.180 ms/op

Iteration   3: 4.715 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   2.232 ms/op
                 listUser·p0.50:   4.497 ms/op
                 listUser·p0.90:   5.226 ms/op
                 listUser·p0.95:   5.972 ms/op
                 listUser·p0.99:   8.684 ms/op
                 listUser·p0.999:  19.825 ms/op
                 listUser·p0.9999: 21.445 ms/op
                 listUser·p1.00:   23.658 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 198584
  mean =      4.828 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9 
    [ 2.500,  5.000) = 158885 
    [ 5.000,  7.500) = 32890 
    [ 7.500, 10.000) = 5479 
    [10.000, 12.500) = 760 
    [12.500, 15.000) = 122 
    [15.000, 17.500) = 112 
    [17.500, 20.000) = 82 
    [20.000, 22.500) = 60 
    [22.500, 25.000) = 107 
    [25.000, 27.500) = 63 
    [27.500, 30.000) = 10 
    [30.000, 32.500) = 5 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.183 ms/op
     p(50.0000) =      4.588 ms/op
     p(90.0000) =      5.390 ms/op
     p(95.0000) =      6.480 ms/op
     p(99.0000) =      9.388 ms/op
     p(99.9000) =     21.392 ms/op
     p(99.9900) =     27.118 ms/op
     p(99.9990) =     31.397 ms/op
     p(99.9999) =     31.785 ms/op
    p(100.0000) =     31.785 ms/op


# Run complete. Total time: 00:13:17

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.529 ± 8.342  ops/ms
ClientPb.existUser                       thrpt       3   7.996 ± 6.158  ops/ms
ClientPb.getUser                         thrpt       3   8.053 ± 3.379  ops/ms
ClientPb.listUser                        thrpt       3   6.550 ± 3.362  ops/ms
ClientPb.createUser                       avgt       3   3.995 ± 2.226   ms/op
ClientPb.existUser                        avgt       3   3.879 ± 1.293   ms/op
ClientPb.getUser                          avgt       3   4.151 ± 1.094   ms/op
ClientPb.listUser                         avgt       3   4.722 ± 2.126   ms/op
ClientPb.createUser                     sample  230802   4.160 ± 0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.690           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.924           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.833           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.652           ms/op
ClientPb.createUser:createUser·p0.99    sample           8.389           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.451           ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.127           ms/op
ClientPb.createUser:createUser·p1.00    sample          33.391           ms/op
ClientPb.existUser                      sample  243351   3.944 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.753           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.740           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.620           ms/op
ClientPb.existUser:existUser·p0.95      sample           5.292           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.471           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.773           ms/op
ClientPb.existUser:existUser·p0.9999    sample          32.102           ms/op
ClientPb.existUser:existUser·p1.00      sample          34.537           ms/op
ClientPb.getUser                        sample  237988   4.033 ± 0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.648           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.826           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.710           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.612           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.987           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.728           ms/op
ClientPb.getUser:getUser·p0.9999        sample          34.813           ms/op
ClientPb.getUser:getUser·p1.00          sample          39.125           ms/op
ClientPb.listUser                       sample  198584   4.828 ± 0.009   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.183           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.588           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.390           ms/op
ClientPb.listUser:listUser·p0.95        sample           6.480           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.388           ms/op
ClientPb.listUser:listUser·p0.999       sample          21.392           ms/op
ClientPb.listUser:listUser·p0.9999      sample          27.118           ms/op
ClientPb.listUser:listUser·p1.00        sample          31.785           ms/op
