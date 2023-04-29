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
# Warmup Iteration   1: 0.995 ops/ms
# Warmup Iteration   2: 2.050 ops/ms
# Warmup Iteration   3: 4.470 ops/ms
Iteration   1: 5.410 ops/ms
Iteration   2: 5.617 ops/ms
Iteration   3: 5.671 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.566 ±(99.9%) 2.520 ops/ms [Average]
  (min, avg, max) = (5.410, 5.566, 5.671), stdev = 0.138
  CI (99.9%): [3.046, 8.086] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 1.377 ops/ms
# Warmup Iteration   2: 4.775 ops/ms
# Warmup Iteration   3: 5.662 ops/ms
Iteration   1: 6.028 ops/ms
Iteration   2: 6.047 ops/ms
Iteration   3: 6.046 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.040 ±(99.9%) 0.191 ops/ms [Average]
  (min, avg, max) = (6.028, 6.040, 6.047), stdev = 0.010
  CI (99.9%): [5.849, 6.231] (assumes normal distribution)


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
# Warmup Iteration   1: 1.397 ops/ms
# Warmup Iteration   2: 3.884 ops/ms
# Warmup Iteration   3: 5.196 ops/ms
Iteration   1: 5.219 ops/ms
Iteration   2: 5.298 ops/ms
Iteration   3: 5.501 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.339 ±(99.9%) 2.652 ops/ms [Average]
  (min, avg, max) = (5.219, 5.339, 5.501), stdev = 0.145
  CI (99.9%): [2.687, 7.991] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:57
# Fork: 1 of 1
# Warmup Iteration   1: 1.386 ops/ms
# Warmup Iteration   2: 3.709 ops/ms
# Warmup Iteration   3: 4.443 ops/ms
Iteration   1: 4.701 ops/ms
Iteration   2: 4.650 ops/ms
Iteration   3: 4.704 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.685 ±(99.9%) 0.555 ops/ms [Average]
  (min, avg, max) = (4.650, 4.685, 4.704), stdev = 0.030
  CI (99.9%): [4.130, 5.239] (assumes normal distribution)


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
# Warmup Iteration   1: 20.271 ±(99.9%) 0.129 ms/op
# Warmup Iteration   2: 7.802 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 6.327 ±(99.9%) 0.014 ms/op
Iteration   1: 5.961 ±(99.9%) 0.019 ms/op
Iteration   2: 6.164 ±(99.9%) 0.012 ms/op
Iteration   3: 5.707 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.944 ±(99.9%) 4.181 ms/op [Average]
  (min, avg, max) = (5.707, 5.944, 6.164), stdev = 0.229
  CI (99.9%): [1.763, 10.126] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:46
# Fork: 1 of 1
# Warmup Iteration   1: 15.977 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 6.121 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 5.776 ±(99.9%) 0.010 ms/op
Iteration   1: 5.550 ±(99.9%) 0.011 ms/op
Iteration   2: 5.453 ±(99.9%) 0.009 ms/op
Iteration   3: 5.569 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.524 ±(99.9%) 1.142 ms/op [Average]
  (min, avg, max) = (5.453, 5.524, 5.569), stdev = 0.063
  CI (99.9%): [4.382, 6.666] (assumes normal distribution)


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
# Warmup Iteration   1: 21.418 ±(99.9%) 0.115 ms/op
# Warmup Iteration   2: 6.914 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 6.090 ±(99.9%) 0.009 ms/op
Iteration   1: 5.876 ±(99.9%) 0.008 ms/op
Iteration   2: 5.592 ±(99.9%) 0.013 ms/op
Iteration   3: 5.476 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.648 ±(99.9%) 3.746 ms/op [Average]
  (min, avg, max) = (5.476, 5.648, 5.876), stdev = 0.205
  CI (99.9%): [1.902, 9.394] (assumes normal distribution)


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
# Warmup Iteration   1: 22.927 ±(99.9%) 0.089 ms/op
# Warmup Iteration   2: 8.123 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 6.630 ±(99.9%) 0.021 ms/op
Iteration   1: 6.590 ±(99.9%) 0.011 ms/op
Iteration   2: 6.410 ±(99.9%) 0.022 ms/op
Iteration   3: 6.862 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.620 ±(99.9%) 4.153 ms/op [Average]
  (min, avg, max) = (6.410, 6.620, 6.862), stdev = 0.228
  CI (99.9%): [2.467, 10.774] (assumes normal distribution)


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
# Warmup Iteration   1: 18.513 ±(99.9%) 0.345 ms/op
# Warmup Iteration   2: 7.933 ±(99.9%) 0.062 ms/op
# Warmup Iteration   3: 5.998 ±(99.9%) 0.027 ms/op
Iteration   1: 5.646 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   0.458 ms/op
                 createUser·p0.50:   5.349 ms/op
                 createUser·p0.90:   7.029 ms/op
                 createUser·p0.95:   8.094 ms/op
                 createUser·p0.99:   10.715 ms/op
                 createUser·p0.999:  24.445 ms/op
                 createUser·p0.9999: 27.286 ms/op
                 createUser·p1.00:   27.918 ms/op

Iteration   2: 5.449 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   2.744 ms/op
                 createUser·p0.50:   5.153 ms/op
                 createUser·p0.90:   6.726 ms/op
                 createUser·p0.95:   7.643 ms/op
                 createUser·p0.99:   10.605 ms/op
                 createUser·p0.999:  26.957 ms/op
                 createUser·p0.9999: 33.882 ms/op
                 createUser·p1.00:   34.669 ms/op

Iteration   3: 5.730 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   2.707 ms/op
                 createUser·p0.50:   5.439 ms/op
                 createUser·p0.90:   7.070 ms/op
                 createUser·p0.95:   7.758 ms/op
                 createUser·p0.99:   10.093 ms/op
                 createUser·p0.999:  29.682 ms/op
                 createUser·p0.9999: 37.645 ms/op
                 createUser·p1.00:   38.339 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 171098
  mean =      5.606 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9 
    [ 2.500,  5.000) = 54504 
    [ 5.000,  7.500) = 105582 
    [ 7.500, 10.000) = 8842 
    [10.000, 12.500) = 1480 
    [12.500, 15.000) = 397 
    [15.000, 17.500) = 61 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 50 
    [27.500, 30.000) = 31 
    [30.000, 32.500) = 29 
    [32.500, 35.000) = 30 
    [35.000, 37.500) = 23 

  Percentiles, ms/op:
      p(0.0000) =      0.458 ms/op
     p(50.0000) =      5.300 ms/op
     p(90.0000) =      6.963 ms/op
     p(95.0000) =      7.823 ms/op
     p(99.0000) =     10.486 ms/op
     p(99.9000) =     24.969 ms/op
     p(99.9900) =     35.841 ms/op
     p(99.9990) =     38.245 ms/op
     p(99.9999) =     38.339 ms/op
    p(100.0000) =     38.339 ms/op


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
# Warmup Iteration   1: 18.946 ±(99.9%) 0.369 ms/op
# Warmup Iteration   2: 6.972 ±(99.9%) 0.049 ms/op
# Warmup Iteration   3: 5.964 ±(99.9%) 0.026 ms/op
Iteration   1: 5.573 ±(99.9%) 0.023 ms/op
                 existUser·p0.00:   0.546 ms/op
                 existUser·p0.50:   5.136 ms/op
                 existUser·p0.90:   7.283 ms/op
                 existUser·p0.95:   8.585 ms/op
                 existUser·p0.99:   11.747 ms/op
                 existUser·p0.999:  25.810 ms/op
                 existUser·p0.9999: 33.270 ms/op
                 existUser·p1.00:   34.013 ms/op

Iteration   2: 5.450 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   2.535 ms/op
                 existUser·p0.50:   5.079 ms/op
                 existUser·p0.90:   6.758 ms/op
                 existUser·p0.95:   7.848 ms/op
                 existUser·p0.99:   11.666 ms/op
                 existUser·p0.999:  30.353 ms/op
                 existUser·p0.9999: 33.894 ms/op
                 existUser·p1.00:   35.521 ms/op

Iteration   3: 5.664 ±(99.9%) 0.024 ms/op
                 existUser·p0.00:   1.866 ms/op
                 existUser·p0.50:   5.243 ms/op
                 existUser·p0.90:   7.250 ms/op
                 existUser·p0.95:   8.356 ms/op
                 existUser·p0.99:   12.967 ms/op
                 existUser·p0.999:  20.316 ms/op
                 existUser·p0.9999: 37.379 ms/op
                 existUser·p1.00:   37.618 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 172493
  mean =      5.561 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14 
    [ 2.500,  5.000) = 71826 
    [ 5.000,  7.500) = 86879 
    [ 7.500, 10.000) = 10422 
    [10.000, 12.500) = 1829 
    [12.500, 15.000) = 966 
    [15.000, 17.500) = 332 
    [17.500, 20.000) = 34 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 16 
    [27.500, 30.000) = 20 
    [30.000, 32.500) = 62 
    [32.500, 35.000) = 50 
    [35.000, 37.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      0.546 ms/op
     p(50.0000) =      5.145 ms/op
     p(90.0000) =      7.086 ms/op
     p(95.0000) =      8.307 ms/op
     p(99.0000) =     12.091 ms/op
     p(99.9000) =     20.791 ms/op
     p(99.9900) =     34.161 ms/op
     p(99.9990) =     37.618 ms/op
     p(99.9999) =     37.618 ms/op
    p(100.0000) =     37.618 ms/op


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
# Warmup Iteration   1: 20.235 ±(99.9%) 0.338 ms/op
# Warmup Iteration   2: 7.104 ±(99.9%) 0.049 ms/op
# Warmup Iteration   3: 6.005 ±(99.9%) 0.023 ms/op
Iteration   1: 5.914 ±(99.9%) 0.028 ms/op
                 getUser·p0.00:   2.318 ms/op
                 getUser·p0.50:   5.456 ms/op
                 getUser·p0.90:   7.414 ms/op
                 getUser·p0.95:   9.159 ms/op
                 getUser·p0.99:   14.451 ms/op
                 getUser·p0.999:  28.168 ms/op
                 getUser·p0.9999: 32.367 ms/op
                 getUser·p1.00:   34.996 ms/op

Iteration   2: 5.924 ±(99.9%) 0.026 ms/op
                 getUser·p0.00:   2.900 ms/op
                 getUser·p0.50:   5.480 ms/op
                 getUser·p0.90:   7.463 ms/op
                 getUser·p0.95:   8.832 ms/op
                 getUser·p0.99:   13.016 ms/op
                 getUser·p0.999:  28.576 ms/op
                 getUser·p0.9999: 34.263 ms/op
                 getUser·p1.00:   37.028 ms/op

Iteration   3: 5.807 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   2.474 ms/op
                 getUser·p0.50:   5.530 ms/op
                 getUser·p0.90:   7.053 ms/op
                 getUser·p0.95:   8.053 ms/op
                 getUser·p0.99:   10.825 ms/op
                 getUser·p0.999:  16.941 ms/op
                 getUser·p0.9999: 33.603 ms/op
                 getUser·p1.00:   34.734 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 163112
  mean =      5.881 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2 
    [ 2.500,  5.000) = 35721 
    [ 5.000,  7.500) = 113036 
    [ 7.500, 10.000) = 9812 
    [10.000, 12.500) = 2842 
    [12.500, 15.000) = 830 
    [15.000, 17.500) = 458 
    [17.500, 20.000) = 144 
    [20.000, 22.500) = 38 
    [22.500, 25.000) = 45 
    [25.000, 27.500) = 28 
    [27.500, 30.000) = 63 
    [30.000, 32.500) = 62 
    [32.500, 35.000) = 29 
    [35.000, 37.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      2.318 ms/op
     p(50.0000) =      5.497 ms/op
     p(90.0000) =      7.266 ms/op
     p(95.0000) =      8.667 ms/op
     p(99.0000) =     12.632 ms/op
     p(99.9000) =     26.932 ms/op
     p(99.9900) =     33.380 ms/op
     p(99.9990) =     35.828 ms/op
     p(99.9999) =     37.028 ms/op
    p(100.0000) =     37.028 ms/op


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
# Warmup Iteration   1: 21.518 ±(99.9%) 0.376 ms/op
# Warmup Iteration   2: 9.788 ±(99.9%) 0.085 ms/op
# Warmup Iteration   3: 6.965 ±(99.9%) 0.031 ms/op
Iteration   1: 6.698 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   2.847 ms/op
                 listUser·p0.50:   6.332 ms/op
                 listUser·p0.90:   7.987 ms/op
                 listUser·p0.95:   9.388 ms/op
                 listUser·p0.99:   12.894 ms/op
                 listUser·p0.999:  30.409 ms/op
                 listUser·p0.9999: 36.043 ms/op
                 listUser·p1.00:   37.093 ms/op

Iteration   2: 6.958 ±(99.9%) 0.029 ms/op
                 listUser·p0.00:   2.032 ms/op
                 listUser·p0.50:   6.619 ms/op
                 listUser·p0.90:   8.298 ms/op
                 listUser·p0.95:   9.486 ms/op
                 listUser·p0.99:   13.406 ms/op
                 listUser·p0.999:  33.328 ms/op
                 listUser·p0.9999: 35.966 ms/op
                 listUser·p1.00:   37.683 ms/op

Iteration   3: 6.924 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   2.748 ms/op
                 listUser·p0.50:   6.586 ms/op
                 listUser·p0.90:   8.298 ms/op
                 listUser·p0.95:   9.470 ms/op
                 listUser·p0.99:   12.780 ms/op
                 listUser·p0.999:  31.991 ms/op
                 listUser·p0.9999: 37.184 ms/op
                 listUser·p1.00:   37.356 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 139956
  mean =      6.858 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2 
    [ 2.500,  5.000) = 2401 
    [ 5.000,  7.500) = 112224 
    [ 7.500, 10.000) = 19960 
    [10.000, 12.500) = 3621 
    [12.500, 15.000) = 1032 
    [15.000, 17.500) = 317 
    [17.500, 20.000) = 87 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 17 
    [27.500, 30.000) = 67 
    [30.000, 32.500) = 79 
    [32.500, 35.000) = 90 
    [35.000, 37.500) = 34 

  Percentiles, ms/op:
      p(0.0000) =      2.032 ms/op
     p(50.0000) =      6.513 ms/op
     p(90.0000) =      8.217 ms/op
     p(95.0000) =      9.454 ms/op
     p(99.0000) =     13.074 ms/op
     p(99.9000) =     31.982 ms/op
     p(99.9900) =     36.635 ms/op
     p(99.9990) =     37.552 ms/op
     p(99.9999) =     37.683 ms/op
    p(100.0000) =     37.683 ms/op


# Run complete. Total time: 00:13:18

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.566 ± 2.520  ops/ms
ClientPb.existUser                       thrpt       3   6.040 ± 0.191  ops/ms
ClientPb.getUser                         thrpt       3   5.339 ± 2.652  ops/ms
ClientPb.listUser                        thrpt       3   4.685 ± 0.555  ops/ms
ClientPb.createUser                       avgt       3   5.944 ± 4.181   ms/op
ClientPb.existUser                        avgt       3   5.524 ± 1.142   ms/op
ClientPb.getUser                          avgt       3   5.648 ± 3.746   ms/op
ClientPb.listUser                         avgt       3   6.620 ± 4.153   ms/op
ClientPb.createUser                     sample  171098   5.606 ± 0.012   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.458           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.300           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.963           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.823           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.486           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.969           ms/op
ClientPb.createUser:createUser·p0.9999  sample          35.841           ms/op
ClientPb.createUser:createUser·p1.00    sample          38.339           ms/op
ClientPb.existUser                      sample  172493   5.561 ± 0.013   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.546           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.145           ms/op
ClientPb.existUser:existUser·p0.90      sample           7.086           ms/op
ClientPb.existUser:existUser·p0.95      sample           8.307           ms/op
ClientPb.existUser:existUser·p0.99      sample          12.091           ms/op
ClientPb.existUser:existUser·p0.999     sample          20.791           ms/op
ClientPb.existUser:existUser·p0.9999    sample          34.161           ms/op
ClientPb.existUser:existUser·p1.00      sample          37.618           ms/op
ClientPb.getUser                        sample  163112   5.881 ± 0.014   ms/op
ClientPb.getUser:getUser·p0.00          sample           2.318           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.497           ms/op
ClientPb.getUser:getUser·p0.90          sample           7.266           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.667           ms/op
ClientPb.getUser:getUser·p0.99          sample          12.632           ms/op
ClientPb.getUser:getUser·p0.999         sample          26.932           ms/op
ClientPb.getUser:getUser·p0.9999        sample          33.380           ms/op
ClientPb.getUser:getUser·p1.00          sample          37.028           ms/op
ClientPb.listUser                       sample  139956   6.858 ± 0.016   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.032           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.513           ms/op
ClientPb.listUser:listUser·p0.90        sample           8.217           ms/op
ClientPb.listUser:listUser·p0.95        sample           9.454           ms/op
ClientPb.listUser:listUser·p0.99        sample          13.074           ms/op
ClientPb.listUser:listUser·p0.999       sample          31.982           ms/op
ClientPb.listUser:listUser·p0.9999      sample          36.635           ms/op
ClientPb.listUser:listUser·p1.00        sample          37.683           ms/op
