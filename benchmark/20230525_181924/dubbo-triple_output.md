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
# Warmup Iteration   1: 1.227 ops/ms
# Warmup Iteration   2: 3.716 ops/ms
# Warmup Iteration   3: 6.671 ops/ms
Iteration   1: 6.303 ops/ms
Iteration   2: 6.728 ops/ms
Iteration   3: 6.767 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.599 ±(99.9%) 4.698 ops/ms [Average]
  (min, avg, max) = (6.303, 6.599, 6.767), stdev = 0.258
  CI (99.9%): [1.901, 11.297] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:11
# Fork: 1 of 1
# Warmup Iteration   1: 1.756 ops/ms
# Warmup Iteration   2: 5.828 ops/ms
# Warmup Iteration   3: 6.880 ops/ms
Iteration   1: 6.888 ops/ms
Iteration   2: 6.999 ops/ms
Iteration   3: 7.057 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.981 ±(99.9%) 1.559 ops/ms [Average]
  (min, avg, max) = (6.888, 6.981, 7.057), stdev = 0.085
  CI (99.9%): [5.422, 8.541] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:04
# Fork: 1 of 1
# Warmup Iteration   1: 1.655 ops/ms
# Warmup Iteration   2: 5.182 ops/ms
# Warmup Iteration   3: 6.482 ops/ms
Iteration   1: 6.248 ops/ms
Iteration   2: 6.467 ops/ms
Iteration   3: 6.593 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.436 ±(99.9%) 3.193 ops/ms [Average]
  (min, avg, max) = (6.248, 6.436, 6.593), stdev = 0.175
  CI (99.9%): [3.243, 9.629] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 1.709 ops/ms
# Warmup Iteration   2: 4.052 ops/ms
# Warmup Iteration   3: 5.868 ops/ms
Iteration   1: 5.291 ops/ms
Iteration   2: 5.631 ops/ms
Iteration   3: 5.856 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.593 ±(99.9%) 5.189 ops/ms [Average]
  (min, avg, max) = (5.291, 5.593, 5.856), stdev = 0.284
  CI (99.9%): [0.404, 10.781] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:50
# Fork: 1 of 1
# Warmup Iteration   1: 17.044 ±(99.9%) 0.081 ms/op
# Warmup Iteration   2: 5.578 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.344 ±(99.9%) 0.010 ms/op
Iteration   1: 4.800 ±(99.9%) 0.013 ms/op
Iteration   2: 4.830 ±(99.9%) 0.017 ms/op
Iteration   3: 4.900 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.843 ±(99.9%) 0.929 ms/op [Average]
  (min, avg, max) = (4.800, 4.843, 4.900), stdev = 0.051
  CI (99.9%): [3.914, 5.772] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 15.753 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 5.337 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.877 ±(99.9%) 0.012 ms/op
Iteration   1: 4.574 ±(99.9%) 0.018 ms/op
Iteration   2: 4.608 ±(99.9%) 0.018 ms/op
Iteration   3: 4.651 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.611 ±(99.9%) 0.708 ms/op [Average]
  (min, avg, max) = (4.574, 4.611, 4.651), stdev = 0.039
  CI (99.9%): [3.903, 5.319] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 15.430 ±(99.9%) 0.074 ms/op
# Warmup Iteration   2: 5.429 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.911 ±(99.9%) 0.015 ms/op
Iteration   1: 5.064 ±(99.9%) 0.010 ms/op
Iteration   2: 4.637 ±(99.9%) 0.014 ms/op
Iteration   3: 4.623 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.775 ±(99.9%) 4.575 ms/op [Average]
  (min, avg, max) = (4.623, 4.775, 5.064), stdev = 0.251
  CI (99.9%): [0.199, 9.350] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 18.340 ±(99.9%) 0.074 ms/op
# Warmup Iteration   2: 6.846 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 5.628 ±(99.9%) 0.016 ms/op
Iteration   1: 5.865 ±(99.9%) 0.018 ms/op
Iteration   2: 5.589 ±(99.9%) 0.016 ms/op
Iteration   3: 5.799 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.751 ±(99.9%) 2.625 ms/op [Average]
  (min, avg, max) = (5.589, 5.751, 5.865), stdev = 0.144
  CI (99.9%): [3.126, 8.376] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 15.452 ±(99.9%) 0.236 ms/op
# Warmup Iteration   2: 6.167 ±(99.9%) 0.033 ms/op
# Warmup Iteration   3: 5.529 ±(99.9%) 0.025 ms/op
Iteration   1: 4.867 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   2.212 ms/op
                 createUser·p0.50:   4.661 ms/op
                 createUser·p0.90:   5.792 ms/op
                 createUser·p0.95:   6.357 ms/op
                 createUser·p0.99:   9.241 ms/op
                 createUser·p0.999:  22.358 ms/op
                 createUser·p0.9999: 24.501 ms/op
                 createUser·p1.00:   25.952 ms/op

Iteration   2: 4.903 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.438 ms/op
                 createUser·p0.50:   4.694 ms/op
                 createUser·p0.90:   5.841 ms/op
                 createUser·p0.95:   6.447 ms/op
                 createUser·p0.99:   8.774 ms/op
                 createUser·p0.999:  19.263 ms/op
                 createUser·p0.9999: 26.590 ms/op
                 createUser·p1.00:   27.329 ms/op

Iteration   3: 4.955 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.303 ms/op
                 createUser·p0.50:   4.825 ms/op
                 createUser·p0.90:   5.865 ms/op
                 createUser·p0.95:   6.332 ms/op
                 createUser·p0.99:   8.389 ms/op
                 createUser·p0.999:  19.121 ms/op
                 createUser·p0.9999: 30.656 ms/op
                 createUser·p1.00:   32.080 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 195409
  mean =      4.908 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 99 
    [ 2.500,  5.000) = 127466 
    [ 5.000,  7.500) = 63582 
    [ 7.500, 10.000) = 3186 
    [10.000, 12.500) = 652 
    [12.500, 15.000) = 151 
    [15.000, 17.500) = 51 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 88 
    [25.000, 27.500) = 63 
    [27.500, 30.000) = 22 
    [30.000, 32.500) = 16 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.303 ms/op
     p(50.0000) =      4.727 ms/op
     p(90.0000) =      5.833 ms/op
     p(95.0000) =      6.373 ms/op
     p(99.0000) =      8.815 ms/op
     p(99.9000) =     22.348 ms/op
     p(99.9900) =     29.637 ms/op
     p(99.9990) =     31.330 ms/op
     p(99.9999) =     32.080 ms/op
    p(100.0000) =     32.080 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 15.341 ±(99.9%) 0.244 ms/op
# Warmup Iteration   2: 5.430 ±(99.9%) 0.032 ms/op
# Warmup Iteration   3: 4.753 ±(99.9%) 0.015 ms/op
Iteration   1: 4.764 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   1.989 ms/op
                 existUser·p0.50:   4.530 ms/op
                 existUser·p0.90:   5.849 ms/op
                 existUser·p0.95:   6.504 ms/op
                 existUser·p0.99:   8.765 ms/op
                 existUser·p0.999:  16.984 ms/op
                 existUser·p0.9999: 25.077 ms/op
                 existUser·p1.00:   25.297 ms/op

Iteration   2: 4.645 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.634 ms/op
                 existUser·p0.50:   4.440 ms/op
                 existUser·p0.90:   5.472 ms/op
                 existUser·p0.95:   6.300 ms/op
                 existUser·p0.99:   8.569 ms/op
                 existUser·p0.999:  16.127 ms/op
                 existUser·p0.9999: 25.362 ms/op
                 existUser·p1.00:   26.935 ms/op

Iteration   3: 4.771 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   2.046 ms/op
                 existUser·p0.50:   4.555 ms/op
                 existUser·p0.90:   5.767 ms/op
                 existUser·p0.95:   6.529 ms/op
                 existUser·p0.99:   9.011 ms/op
                 existUser·p0.999:  13.550 ms/op
                 existUser·p0.9999: 30.015 ms/op
                 existUser·p1.00:   30.867 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 203012
  mean =      4.726 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 101 
    [ 2.500,  5.000) = 153968 
    [ 5.000,  7.500) = 44887 
    [ 7.500, 10.000) = 2801 
    [10.000, 12.500) = 813 
    [12.500, 15.000) = 215 
    [15.000, 17.500) = 35 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 103 
    [25.000, 27.500) = 37 
    [27.500, 30.000) = 13 
    [30.000, 32.500) = 7 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.634 ms/op
     p(50.0000) =      4.506 ms/op
     p(90.0000) =      5.718 ms/op
     p(95.0000) =      6.447 ms/op
     p(99.0000) =      8.864 ms/op
     p(99.9000) =     16.170 ms/op
     p(99.9900) =     27.920 ms/op
     p(99.9990) =     30.792 ms/op
     p(99.9999) =     30.867 ms/op
    p(100.0000) =     30.867 ms/op


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
# Warmup Iteration   1: 15.059 ±(99.9%) 0.230 ms/op
# Warmup Iteration   2: 5.830 ±(99.9%) 0.032 ms/op
# Warmup Iteration   3: 5.029 ±(99.9%) 0.016 ms/op
Iteration   1: 5.021 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   2.515 ms/op
                 getUser·p0.50:   4.653 ms/op
                 getUser·p0.90:   6.210 ms/op
                 getUser·p0.95:   7.774 ms/op
                 getUser·p0.99:   11.174 ms/op
                 getUser·p0.999:  22.849 ms/op
                 getUser·p0.9999: 31.335 ms/op
                 getUser·p1.00:   32.113 ms/op

Iteration   2: 5.112 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   2.343 ms/op
                 getUser·p0.50:   4.866 ms/op
                 getUser·p0.90:   6.398 ms/op
                 getUser·p0.95:   7.094 ms/op
                 getUser·p0.99:   9.044 ms/op
                 getUser·p0.999:  23.243 ms/op
                 getUser·p0.9999: 28.286 ms/op
                 getUser·p1.00:   29.557 ms/op

Iteration   3: 4.821 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   2.314 ms/op
                 getUser·p0.50:   4.661 ms/op
                 getUser·p0.90:   5.562 ms/op
                 getUser·p0.95:   5.997 ms/op
                 getUser·p0.99:   8.167 ms/op
                 getUser·p0.999:  13.838 ms/op
                 getUser·p0.9999: 30.671 ms/op
                 getUser·p1.00:   32.571 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 192635
  mean =      4.982 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9 
    [ 2.500,  5.000) = 126589 
    [ 5.000,  7.500) = 59042 
    [ 7.500, 10.000) = 5372 
    [10.000, 12.500) = 960 
    [12.500, 15.000) = 398 
    [15.000, 17.500) = 41 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 41 
    [25.000, 27.500) = 90 
    [27.500, 30.000) = 32 
    [30.000, 32.500) = 28 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.314 ms/op
     p(50.0000) =      4.719 ms/op
     p(90.0000) =      6.021 ms/op
     p(95.0000) =      6.980 ms/op
     p(99.0000) =      9.732 ms/op
     p(99.9000) =     20.797 ms/op
     p(99.9900) =     30.671 ms/op
     p(99.9990) =     32.146 ms/op
     p(99.9999) =     32.571 ms/op
    p(100.0000) =     32.571 ms/op


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
# Warmup Iteration   1: 17.004 ±(99.9%) 0.252 ms/op
# Warmup Iteration   2: 7.037 ±(99.9%) 0.045 ms/op
# Warmup Iteration   3: 5.658 ±(99.9%) 0.020 ms/op
Iteration   1: 5.812 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   2.806 ms/op
                 listUser·p0.50:   5.546 ms/op
                 listUser·p0.90:   7.029 ms/op
                 listUser·p0.95:   8.020 ms/op
                 listUser·p0.99:   10.486 ms/op
                 listUser·p0.999:  24.347 ms/op
                 listUser·p0.9999: 27.738 ms/op
                 listUser·p1.00:   29.032 ms/op

Iteration   2: 5.594 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   2.769 ms/op
                 listUser·p0.50:   5.325 ms/op
                 listUser·p0.90:   6.636 ms/op
                 listUser·p0.95:   7.381 ms/op
                 listUser·p0.99:   9.814 ms/op
                 listUser·p0.999:  26.220 ms/op
                 listUser·p0.9999: 29.439 ms/op
                 listUser·p1.00:   30.540 ms/op

Iteration   3: 5.936 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   2.470 ms/op
                 listUser·p0.50:   5.718 ms/op
                 listUser·p0.90:   6.844 ms/op
                 listUser·p0.95:   7.784 ms/op
                 listUser·p0.99:   10.972 ms/op
                 listUser·p0.999:  19.420 ms/op
                 listUser·p0.9999: 28.037 ms/op
                 listUser·p1.00:   29.065 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 166054
  mean =      5.777 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2 
    [ 2.500,  5.000) = 29895 
    [ 5.000,  7.500) = 126510 
    [ 7.500, 10.000) = 7420 
    [10.000, 12.500) = 1607 
    [12.500, 15.000) = 254 
    [15.000, 17.500) = 55 
    [17.500, 20.000) = 45 
    [20.000, 22.500) = 42 
    [22.500, 25.000) = 108 
    [25.000, 27.500) = 64 
    [27.500, 30.000) = 49 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.470 ms/op
     p(50.0000) =      5.530 ms/op
     p(90.0000) =      6.816 ms/op
     p(95.0000) =      7.725 ms/op
     p(99.0000) =     10.486 ms/op
     p(99.9000) =     23.757 ms/op
     p(99.9900) =     28.967 ms/op
     p(99.9990) =     30.518 ms/op
     p(99.9999) =     30.540 ms/op
    p(100.0000) =     30.540 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   6.599 ± 4.698  ops/ms
ClientPb.existUser                       thrpt       3   6.981 ± 1.559  ops/ms
ClientPb.getUser                         thrpt       3   6.436 ± 3.193  ops/ms
ClientPb.listUser                        thrpt       3   5.593 ± 5.189  ops/ms
ClientPb.createUser                       avgt       3   4.843 ± 0.929   ms/op
ClientPb.existUser                        avgt       3   4.611 ± 0.708   ms/op
ClientPb.getUser                          avgt       3   4.775 ± 4.575   ms/op
ClientPb.listUser                         avgt       3   5.751 ± 2.625   ms/op
ClientPb.createUser                     sample  195409   4.908 ± 0.009   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.303           ms/op
ClientPb.createUser:createUser·p0.50    sample           4.727           ms/op
ClientPb.createUser:createUser·p0.90    sample           5.833           ms/op
ClientPb.createUser:createUser·p0.95    sample           6.373           ms/op
ClientPb.createUser:createUser·p0.99    sample           8.815           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.348           ms/op
ClientPb.createUser:createUser·p0.9999  sample          29.637           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.080           ms/op
ClientPb.existUser                      sample  203012   4.726 ± 0.008   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.634           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.506           ms/op
ClientPb.existUser:existUser·p0.90      sample           5.718           ms/op
ClientPb.existUser:existUser·p0.95      sample           6.447           ms/op
ClientPb.existUser:existUser·p0.99      sample           8.864           ms/op
ClientPb.existUser:existUser·p0.999     sample          16.170           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.920           ms/op
ClientPb.existUser:existUser·p1.00      sample          30.867           ms/op
ClientPb.getUser                        sample  192635   4.982 ± 0.010   ms/op
ClientPb.getUser:getUser·p0.00          sample           2.314           ms/op
ClientPb.getUser:getUser·p0.50          sample           4.719           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.021           ms/op
ClientPb.getUser:getUser·p0.95          sample           6.980           ms/op
ClientPb.getUser:getUser·p0.99          sample           9.732           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.797           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.671           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.571           ms/op
ClientPb.listUser                       sample  166054   5.777 ± 0.011   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.470           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.530           ms/op
ClientPb.listUser:listUser·p0.90        sample           6.816           ms/op
ClientPb.listUser:listUser·p0.95        sample           7.725           ms/op
ClientPb.listUser:listUser·p0.99        sample          10.486           ms/op
ClientPb.listUser:listUser·p0.999       sample          23.757           ms/op
ClientPb.listUser:listUser·p0.9999      sample          28.967           ms/op
ClientPb.listUser:listUser·p1.00        sample          30.540           ms/op
