# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.199 ops/ms
# Warmup Iteration   2: 5.980 ops/ms
# Warmup Iteration   3: 8.427 ops/ms
Iteration   1: 9.058 ops/ms
Iteration   2: 9.344 ops/ms
Iteration   3: 9.177 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.193 ±(99.9%) 2.618 ops/ms [Average]
  (min, avg, max) = (9.058, 9.193, 9.344), stdev = 0.144
  CI (99.9%): [6.575, 11.811] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 2.885 ops/ms
# Warmup Iteration   2: 8.656 ops/ms
# Warmup Iteration   3: 9.124 ops/ms
Iteration   1: 9.427 ops/ms
Iteration   2: 9.334 ops/ms
Iteration   3: 9.627 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.463 ±(99.9%) 2.734 ops/ms [Average]
  (min, avg, max) = (9.334, 9.463, 9.627), stdev = 0.150
  CI (99.9%): [6.729, 12.197] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.022 ops/ms
# Warmup Iteration   2: 8.325 ops/ms
# Warmup Iteration   3: 8.628 ops/ms
Iteration   1: 9.063 ops/ms
Iteration   2: 9.194 ops/ms
Iteration   3: 8.968 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.075 ±(99.9%) 2.073 ops/ms [Average]
  (min, avg, max) = (8.968, 9.075, 9.194), stdev = 0.114
  CI (99.9%): [7.002, 11.148] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 2.677 ops/ms
# Warmup Iteration   2: 7.132 ops/ms
# Warmup Iteration   3: 7.636 ops/ms
Iteration   1: 7.711 ops/ms
Iteration   2: 7.847 ops/ms
Iteration   3: 7.833 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.797 ±(99.9%) 1.368 ops/ms [Average]
  (min, avg, max) = (7.711, 7.797, 7.847), stdev = 0.075
  CI (99.9%): [6.429, 9.165] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 9.699 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.975 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.695 ±(99.9%) 0.007 ms/op
Iteration   1: 3.596 ±(99.9%) 0.004 ms/op
Iteration   2: 3.527 ±(99.9%) 0.004 ms/op
Iteration   3: 3.485 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.536 ±(99.9%) 1.028 ms/op [Average]
  (min, avg, max) = (3.485, 3.536, 3.596), stdev = 0.056
  CI (99.9%): [2.508, 4.564] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 8.801 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.625 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.340 ±(99.9%) 0.008 ms/op
Iteration   1: 3.290 ±(99.9%) 0.004 ms/op
Iteration   2: 3.319 ±(99.9%) 0.006 ms/op
Iteration   3: 3.384 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.331 ±(99.9%) 0.877 ms/op [Average]
  (min, avg, max) = (3.290, 3.331, 3.384), stdev = 0.048
  CI (99.9%): [2.455, 4.208] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 9.609 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.709 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.585 ±(99.9%) 0.004 ms/op
Iteration   1: 3.400 ±(99.9%) 0.009 ms/op
Iteration   2: 3.477 ±(99.9%) 0.005 ms/op
Iteration   3: 3.376 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.418 ±(99.9%) 0.964 ms/op [Average]
  (min, avg, max) = (3.376, 3.418, 3.477), stdev = 0.053
  CI (99.9%): [2.454, 4.382] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 11.464 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 4.606 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.204 ±(99.9%) 0.006 ms/op
Iteration   1: 4.100 ±(99.9%) 0.006 ms/op
Iteration   2: 3.912 ±(99.9%) 0.014 ms/op
Iteration   3: 4.091 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.034 ±(99.9%) 1.940 ms/op [Average]
  (min, avg, max) = (3.912, 4.034, 4.100), stdev = 0.106
  CI (99.9%): [2.094, 5.975] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 9.728 ±(99.9%) 0.122 ms/op
# Warmup Iteration   2: 4.069 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.595 ±(99.9%) 0.011 ms/op
Iteration   1: 3.497 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.468 ms/op
                 createUser·p0.50:   3.465 ms/op
                 createUser·p0.90:   3.772 ms/op
                 createUser·p0.95:   4.173 ms/op
                 createUser·p0.99:   5.685 ms/op
                 createUser·p0.999:  19.319 ms/op
                 createUser·p0.9999: 29.608 ms/op
                 createUser·p1.00:   30.278 ms/op

Iteration   2: 3.423 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.161 ms/op
                 createUser·p0.50:   3.293 ms/op
                 createUser·p0.90:   3.789 ms/op
                 createUser·p0.95:   4.121 ms/op
                 createUser·p0.99:   5.915 ms/op
                 createUser·p0.999:  19.756 ms/op
                 createUser·p0.9999: 21.987 ms/op
                 createUser·p1.00:   22.577 ms/op

Iteration   3: 3.596 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.669 ms/op
                 createUser·p0.50:   3.408 ms/op
                 createUser·p0.90:   4.235 ms/op
                 createUser·p0.95:   4.563 ms/op
                 createUser·p0.99:   6.585 ms/op
                 createUser·p0.999:  16.777 ms/op
                 createUser·p0.9999: 25.222 ms/op
                 createUser·p1.00:   25.821 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 273980
  mean =      3.504 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8901 
    [ 2.500,  5.000) = 258447 
    [ 5.000,  7.500) = 5242 
    [ 7.500, 10.000) = 867 
    [10.000, 12.500) = 170 
    [12.500, 15.000) = 57 
    [15.000, 17.500) = 35 
    [17.500, 20.000) = 77 
    [20.000, 22.500) = 119 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 11 
    [27.500, 30.000) = 29 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.161 ms/op
     p(50.0000) =      3.420 ms/op
     p(90.0000) =      3.994 ms/op
     p(95.0000) =      4.342 ms/op
     p(99.0000) =      6.169 ms/op
     p(99.9000) =     16.941 ms/op
     p(99.9900) =     28.089 ms/op
     p(99.9990) =     30.148 ms/op
     p(99.9999) =     30.278 ms/op
    p(100.0000) =     30.278 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 7.800 ±(99.9%) 0.099 ms/op
# Warmup Iteration   2: 3.664 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.413 ±(99.9%) 0.009 ms/op
Iteration   1: 3.367 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.493 ms/op
                 existUser·p0.50:   3.244 ms/op
                 existUser·p0.90:   3.740 ms/op
                 existUser·p0.95:   4.071 ms/op
                 existUser·p0.99:   6.067 ms/op
                 existUser·p0.999:  19.515 ms/op
                 existUser·p0.9999: 26.132 ms/op
                 existUser·p1.00:   28.180 ms/op

Iteration   2: 3.322 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.075 ms/op
                 existUser·p0.50:   3.269 ms/op
                 existUser·p0.90:   3.588 ms/op
                 existUser·p0.95:   3.908 ms/op
                 existUser·p0.99:   5.652 ms/op
                 existUser·p0.999:  20.950 ms/op
                 existUser·p0.9999: 24.970 ms/op
                 existUser·p1.00:   26.149 ms/op

Iteration   3: 3.392 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.159 ms/op
                 existUser·p0.50:   3.305 ms/op
                 existUser·p0.90:   3.760 ms/op
                 existUser·p0.95:   4.121 ms/op
                 existUser·p0.99:   6.152 ms/op
                 existUser·p0.999:  11.928 ms/op
                 existUser·p0.9999: 25.559 ms/op
                 existUser·p1.00:   26.771 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 285702
  mean =      3.360 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10304 
    [ 2.500,  5.000) = 269064 
    [ 5.000,  7.500) = 4857 
    [ 7.500, 10.000) = 1042 
    [10.000, 12.500) = 123 
    [12.500, 15.000) = 22 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 74 
    [22.500, 25.000) = 117 
    [25.000, 27.500) = 47 

  Percentiles, ms/op:
      p(0.0000) =      1.075 ms/op
     p(50.0000) =      3.269 ms/op
     p(90.0000) =      3.703 ms/op
     p(95.0000) =      4.039 ms/op
     p(99.0000) =      5.956 ms/op
     p(99.9000) =     15.041 ms/op
     p(99.9900) =     25.559 ms/op
     p(99.9990) =     28.152 ms/op
     p(99.9999) =     28.180 ms/op
    p(100.0000) =     28.180 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 8.960 ±(99.9%) 0.124 ms/op
# Warmup Iteration   2: 3.805 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.560 ±(99.9%) 0.011 ms/op
Iteration   1: 3.513 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.466 ms/op
                 getUser·p0.50:   3.330 ms/op
                 getUser·p0.90:   4.039 ms/op
                 getUser·p0.95:   4.801 ms/op
                 getUser·p0.99:   6.586 ms/op
                 getUser·p0.999:  20.013 ms/op
                 getUser·p0.9999: 23.032 ms/op
                 getUser·p1.00:   23.822 ms/op

Iteration   2: 3.443 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.833 ms/op
                 getUser·p0.50:   3.318 ms/op
                 getUser·p0.90:   3.777 ms/op
                 getUser·p0.95:   4.076 ms/op
                 getUser·p0.99:   6.726 ms/op
                 getUser·p0.999:  23.103 ms/op
                 getUser·p0.9999: 26.500 ms/op
                 getUser·p1.00:   28.049 ms/op

Iteration   3: 3.510 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.227 ms/op
                 getUser·p0.50:   3.359 ms/op
                 getUser·p0.90:   3.994 ms/op
                 getUser·p0.95:   4.891 ms/op
                 getUser·p0.99:   6.873 ms/op
                 getUser·p0.999:  19.419 ms/op
                 getUser·p0.9999: 27.652 ms/op
                 getUser·p1.00:   28.410 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 275215
  mean =      3.489 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8924 
    [ 2.500,  5.000) = 255208 
    [ 5.000,  7.500) = 9466 
    [ 7.500, 10.000) = 1193 
    [10.000, 12.500) = 129 
    [12.500, 15.000) = 3 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 92 
    [22.500, 25.000) = 110 
    [25.000, 27.500) = 56 

  Percentiles, ms/op:
      p(0.0000) =      1.227 ms/op
     p(50.0000) =      3.338 ms/op
     p(90.0000) =      3.936 ms/op
     p(95.0000) =      4.538 ms/op
     p(99.0000) =      6.685 ms/op
     p(99.9000) =     19.810 ms/op
     p(99.9900) =     26.378 ms/op
     p(99.9990) =     27.975 ms/op
     p(99.9999) =     28.410 ms/op
    p(100.0000) =     28.410 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 11.222 ±(99.9%) 0.154 ms/op
# Warmup Iteration   2: 4.653 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.250 ±(99.9%) 0.014 ms/op
Iteration   1: 4.102 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.581 ms/op
                 listUser·p0.50:   3.977 ms/op
                 listUser·p0.90:   4.399 ms/op
                 listUser·p0.95:   4.612 ms/op
                 listUser·p0.99:   7.635 ms/op
                 listUser·p0.999:  20.286 ms/op
                 listUser·p0.9999: 24.419 ms/op
                 listUser·p1.00:   24.740 ms/op

Iteration   2: 4.049 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.281 ms/op
                 listUser·p0.50:   3.920 ms/op
                 listUser·p0.90:   4.325 ms/op
                 listUser·p0.95:   4.538 ms/op
                 listUser·p0.99:   7.545 ms/op
                 listUser·p0.999:  15.466 ms/op
                 listUser·p0.9999: 18.551 ms/op
                 listUser·p1.00:   20.283 ms/op

Iteration   3: 4.139 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.150 ms/op
                 listUser·p0.50:   4.014 ms/op
                 listUser·p0.90:   4.506 ms/op
                 listUser·p0.95:   4.801 ms/op
                 listUser·p0.99:   7.651 ms/op
                 listUser·p0.999:  16.318 ms/op
                 listUser·p0.9999: 21.275 ms/op
                 listUser·p1.00:   21.332 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 234157
  mean =      4.096 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 37 
    [ 2.500,  5.000) = 226309 
    [ 5.000,  7.500) = 5345 
    [ 7.500, 10.000) = 1506 
    [10.000, 12.500) = 379 
    [12.500, 15.000) = 164 
    [15.000, 17.500) = 224 
    [17.500, 20.000) = 99 
    [20.000, 22.500) = 62 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.581 ms/op
     p(50.0000) =      3.965 ms/op
     p(90.0000) =      4.415 ms/op
     p(95.0000) =      4.653 ms/op
     p(99.0000) =      7.619 ms/op
     p(99.9000) =     16.559 ms/op
     p(99.9900) =     22.741 ms/op
     p(99.9990) =     24.598 ms/op
     p(99.9999) =     24.740 ms/op
    p(100.0000) =     24.740 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.193 ± 2.618  ops/ms
ClientPb.existUser                       thrpt       3   9.463 ± 2.734  ops/ms
ClientPb.getUser                         thrpt       3   9.075 ± 2.073  ops/ms
ClientPb.listUser                        thrpt       3   7.797 ± 1.368  ops/ms
ClientPb.createUser                       avgt       3   3.536 ± 1.028   ms/op
ClientPb.existUser                        avgt       3   3.331 ± 0.877   ms/op
ClientPb.getUser                          avgt       3   3.418 ± 0.964   ms/op
ClientPb.listUser                         avgt       3   4.034 ± 1.940   ms/op
ClientPb.createUser                     sample  273980   3.504 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.161           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.420           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.994           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.342           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.169           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.941           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.089           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.278           ms/op
ClientPb.existUser                      sample  285702   3.360 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.075           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.269           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.703           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.039           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.956           ms/op
ClientPb.existUser:existUser·p0.999     sample          15.041           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.559           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.180           ms/op
ClientPb.getUser                        sample  275215   3.489 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.227           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.338           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.936           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.538           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.685           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.810           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.378           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.410           ms/op
ClientPb.listUser                       sample  234157   4.096 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.581           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.965           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.415           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.653           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.619           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.559           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.741           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.740           ms/op
