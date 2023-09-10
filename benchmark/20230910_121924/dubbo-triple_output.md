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
# Warmup Iteration   1: 1.300 ops/ms
# Warmup Iteration   2: 3.412 ops/ms
# Warmup Iteration   3: 6.070 ops/ms
Iteration   1: 5.913 ops/ms
Iteration   2: 6.302 ops/ms
Iteration   3: 6.332 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.182 ±(99.9%) 4.264 ops/ms [Average]
  (min, avg, max) = (5.913, 6.182, 6.332), stdev = 0.234
  CI (99.9%): [1.919, 10.446] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:15
# Fork: 1 of 1
# Warmup Iteration   1: 1.837 ops/ms
# Warmup Iteration   2: 5.643 ops/ms
# Warmup Iteration   3: 6.178 ops/ms
Iteration   1: 6.077 ops/ms
Iteration   2: 6.294 ops/ms
Iteration   3: 6.611 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.327 ±(99.9%) 4.898 ops/ms [Average]
  (min, avg, max) = (6.077, 6.327, 6.611), stdev = 0.268
  CI (99.9%): [1.430, 11.225] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 1.683 ops/ms
# Warmup Iteration   2: 4.835 ops/ms
# Warmup Iteration   3: 5.666 ops/ms
Iteration   1: 5.794 ops/ms
Iteration   2: 5.696 ops/ms
Iteration   3: 6.216 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.902 ±(99.9%) 5.047 ops/ms [Average]
  (min, avg, max) = (5.696, 5.902, 6.216), stdev = 0.277
  CI (99.9%): [0.855, 10.949] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:56
# Fork: 1 of 1
# Warmup Iteration   1: 1.563 ops/ms
# Warmup Iteration   2: 4.135 ops/ms
# Warmup Iteration   3: 5.254 ops/ms
Iteration   1: 4.874 ops/ms
Iteration   2: 5.344 ops/ms
Iteration   3: 4.930 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.049 ±(99.9%) 4.677 ops/ms [Average]
  (min, avg, max) = (4.874, 5.049, 5.344), stdev = 0.256
  CI (99.9%): [0.373, 9.726] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 18.378 ±(99.9%) 0.134 ms/op
# Warmup Iteration   2: 6.841 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 5.954 ±(99.9%) 0.012 ms/op
Iteration   1: 5.559 ±(99.9%) 0.012 ms/op
Iteration   2: 5.495 ±(99.9%) 0.014 ms/op
Iteration   3: 5.335 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.463 ±(99.9%) 2.102 ms/op [Average]
  (min, avg, max) = (5.335, 5.463, 5.559), stdev = 0.115
  CI (99.9%): [3.361, 7.565] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 16.139 ±(99.9%) 0.074 ms/op
# Warmup Iteration   2: 5.569 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 5.395 ±(99.9%) 0.006 ms/op
Iteration   1: 5.004 ±(99.9%) 0.008 ms/op
Iteration   2: 5.071 ±(99.9%) 0.006 ms/op
Iteration   3: 4.793 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.956 ±(99.9%) 2.643 ms/op [Average]
  (min, avg, max) = (4.793, 4.956, 5.071), stdev = 0.145
  CI (99.9%): [2.313, 7.599] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 17.741 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 6.234 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 5.321 ±(99.9%) 0.010 ms/op
Iteration   1: 5.242 ±(99.9%) 0.005 ms/op
Iteration   2: 5.180 ±(99.9%) 0.014 ms/op
Iteration   3: 5.172 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.198 ±(99.9%) 0.698 ms/op [Average]
  (min, avg, max) = (5.172, 5.198, 5.242), stdev = 0.038
  CI (99.9%): [4.500, 5.896] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 17.788 ±(99.9%) 0.066 ms/op
# Warmup Iteration   2: 7.224 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 6.004 ±(99.9%) 0.012 ms/op
Iteration   1: 6.106 ±(99.9%) 0.012 ms/op
Iteration   2: 6.097 ±(99.9%) 0.009 ms/op
Iteration   3: 6.068 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.090 ±(99.9%) 0.368 ms/op [Average]
  (min, avg, max) = (6.068, 6.090, 6.106), stdev = 0.020
  CI (99.9%): [5.723, 6.458] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 16.187 ±(99.9%) 0.233 ms/op
# Warmup Iteration   2: 7.441 ±(99.9%) 0.049 ms/op
# Warmup Iteration   3: 5.705 ±(99.9%) 0.024 ms/op
Iteration   1: 5.403 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   1.556 ms/op
                 createUser·p0.50:   5.079 ms/op
                 createUser·p0.90:   6.758 ms/op
                 createUser·p0.95:   7.848 ms/op
                 createUser·p0.99:   11.485 ms/op
                 createUser·p0.999:  24.242 ms/op
                 createUser·p0.9999: 28.776 ms/op
                 createUser·p1.00:   29.655 ms/op

Iteration   2: 5.287 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   2.216 ms/op
                 createUser·p0.50:   5.038 ms/op
                 createUser·p0.90:   6.488 ms/op
                 createUser·p0.95:   7.332 ms/op
                 createUser·p0.99:   10.306 ms/op
                 createUser·p0.999:  25.578 ms/op
                 createUser·p0.9999: 31.284 ms/op
                 createUser·p1.00:   32.113 ms/op

Iteration   3: 5.389 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   2.040 ms/op
                 createUser·p0.50:   5.087 ms/op
                 createUser·p0.90:   6.726 ms/op
                 createUser·p0.95:   7.725 ms/op
                 createUser·p0.99:   10.600 ms/op
                 createUser·p0.999:  28.628 ms/op
                 createUser·p0.9999: 37.032 ms/op
                 createUser·p1.00:   38.076 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 179024
  mean =      5.359 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 51 
    [ 2.500,  5.000) = 83569 
    [ 5.000,  7.500) = 85722 
    [ 7.500, 10.000) = 7270 
    [10.000, 12.500) = 1543 
    [12.500, 15.000) = 426 
    [15.000, 17.500) = 171 
    [17.500, 20.000) = 68 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 46 
    [27.500, 30.000) = 76 
    [30.000, 32.500) = 23 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 29 

  Percentiles, ms/op:
      p(0.0000) =      1.556 ms/op
     p(50.0000) =      5.063 ms/op
     p(90.0000) =      6.660 ms/op
     p(95.0000) =      7.619 ms/op
     p(99.0000) =     10.846 ms/op
     p(99.9000) =     24.609 ms/op
     p(99.9900) =     36.504 ms/op
     p(99.9990) =     37.921 ms/op
     p(99.9999) =     38.076 ms/op
    p(100.0000) =     38.076 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 16.010 ±(99.9%) 0.224 ms/op
# Warmup Iteration   2: 5.795 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 5.426 ±(99.9%) 0.023 ms/op
Iteration   1: 5.334 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   1.266 ms/op
                 existUser·p0.50:   5.022 ms/op
                 existUser·p0.90:   6.734 ms/op
                 existUser·p0.95:   7.741 ms/op
                 existUser·p0.99:   10.682 ms/op
                 existUser·p0.999:  22.154 ms/op
                 existUser·p0.9999: 26.378 ms/op
                 existUser·p1.00:   27.820 ms/op

Iteration   2: 5.112 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   1.679 ms/op
                 existUser·p0.50:   4.891 ms/op
                 existUser·p0.90:   6.382 ms/op
                 existUser·p0.95:   7.029 ms/op
                 existUser·p0.99:   9.683 ms/op
                 existUser·p0.999:  13.948 ms/op
                 existUser·p0.9999: 33.201 ms/op
                 existUser·p1.00:   33.882 ms/op

Iteration   3: 4.991 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   1.864 ms/op
                 existUser·p0.50:   4.669 ms/op
                 existUser·p0.90:   6.275 ms/op
                 existUser·p0.95:   7.258 ms/op
                 existUser·p0.99:   10.835 ms/op
                 existUser·p0.999:  24.052 ms/op
                 existUser·p0.9999: 30.912 ms/op
                 existUser·p1.00:   31.031 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 186591
  mean =      5.142 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 105 
    [ 2.500,  5.000) = 105588 
    [ 5.000,  7.500) = 72530 
    [ 7.500, 10.000) = 6118 
    [10.000, 12.500) = 1473 
    [12.500, 15.000) = 530 
    [15.000, 17.500) = 75 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 46 
    [25.000, 27.500) = 36 
    [27.500, 30.000) = 21 
    [30.000, 32.500) = 33 
    [32.500, 35.000) = 16 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.266 ms/op
     p(50.0000) =      4.850 ms/op
     p(90.0000) =      6.472 ms/op
     p(95.0000) =      7.343 ms/op
     p(99.0000) =     10.404 ms/op
     p(99.9000) =     16.545 ms/op
     p(99.9900) =     31.480 ms/op
     p(99.9990) =     33.882 ms/op
     p(99.9999) =     33.882 ms/op
    p(100.0000) =     33.882 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 17.611 ±(99.9%) 0.240 ms/op
# Warmup Iteration   2: 5.961 ±(99.9%) 0.032 ms/op
# Warmup Iteration   3: 5.231 ±(99.9%) 0.019 ms/op
Iteration   1: 5.263 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   2.363 ms/op
                 getUser·p0.50:   4.956 ms/op
                 getUser·p0.90:   6.365 ms/op
                 getUser·p0.95:   7.676 ms/op
                 getUser·p0.99:   11.551 ms/op
                 getUser·p0.999:  25.139 ms/op
                 getUser·p0.9999: 28.833 ms/op
                 getUser·p1.00:   29.229 ms/op

Iteration   2: 5.666 ±(99.9%) 0.027 ms/op
                 getUser·p0.00:   1.978 ms/op
                 getUser·p0.50:   5.161 ms/op
                 getUser·p0.90:   7.881 ms/op
                 getUser·p0.95:   9.257 ms/op
                 getUser·p0.99:   13.222 ms/op
                 getUser·p0.999:  26.168 ms/op
                 getUser·p0.9999: 30.217 ms/op
                 getUser·p1.00:   30.835 ms/op

Iteration   3: 5.418 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   2.089 ms/op
                 getUser·p0.50:   5.161 ms/op
                 getUser·p0.90:   6.709 ms/op
                 getUser·p0.95:   7.789 ms/op
                 getUser·p0.99:   10.666 ms/op
                 getUser·p0.999:  16.778 ms/op
                 getUser·p0.9999: 32.408 ms/op
                 getUser·p1.00:   35.193 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 176218
  mean =      5.444 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13 
    [ 2.500,  5.000) = 80837 
    [ 5.000,  7.500) = 82094 
    [ 7.500, 10.000) = 9677 
    [10.000, 12.500) = 2233 
    [12.500, 15.000) = 822 
    [15.000, 17.500) = 216 
    [17.500, 20.000) = 97 
    [20.000, 22.500) = 53 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 65 
    [27.500, 30.000) = 59 
    [30.000, 32.500) = 33 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.978 ms/op
     p(50.0000) =      5.079 ms/op
     p(90.0000) =      6.898 ms/op
     p(95.0000) =      8.339 ms/op
     p(99.0000) =     11.796 ms/op
     p(99.9000) =     22.581 ms/op
     p(99.9900) =     31.109 ms/op
     p(99.9990) =     34.194 ms/op
     p(99.9999) =     35.193 ms/op
    p(100.0000) =     35.193 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 17.866 ±(99.9%) 0.296 ms/op
# Warmup Iteration   2: 6.859 ±(99.9%) 0.037 ms/op
# Warmup Iteration   3: 6.473 ±(99.9%) 0.027 ms/op
Iteration   1: 6.050 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   1.475 ms/op
                 listUser·p0.50:   5.710 ms/op
                 listUser·p0.90:   7.373 ms/op
                 listUser·p0.95:   8.765 ms/op
                 listUser·p0.99:   12.419 ms/op
                 listUser·p0.999:  26.547 ms/op
                 listUser·p0.9999: 29.121 ms/op
                 listUser·p1.00:   29.721 ms/op

Iteration   2: 6.041 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   1.946 ms/op
                 listUser·p0.50:   5.726 ms/op
                 listUser·p0.90:   7.299 ms/op
                 listUser·p0.95:   8.389 ms/op
                 listUser·p0.99:   11.534 ms/op
                 listUser·p0.999:  27.394 ms/op
                 listUser·p0.9999: 30.333 ms/op
                 listUser·p1.00:   30.867 ms/op

Iteration   3: 5.915 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   2.191 ms/op
                 listUser·p0.50:   5.669 ms/op
                 listUser·p0.90:   6.971 ms/op
                 listUser·p0.95:   8.077 ms/op
                 listUser·p0.99:   11.420 ms/op
                 listUser·p0.999:  20.769 ms/op
                 listUser·p0.9999: 23.927 ms/op
                 listUser·p1.00:   25.035 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 159859
  mean =      6.001 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4 
    [ 2.500,  5.000) = 22633 
    [ 5.000,  7.500) = 124317 
    [ 7.500, 10.000) = 9336 
    [10.000, 12.500) = 2392 
    [12.500, 15.000) = 696 
    [15.000, 17.500) = 129 
    [17.500, 20.000) = 53 
    [20.000, 22.500) = 53 
    [22.500, 25.000) = 75 
    [25.000, 27.500) = 86 
    [27.500, 30.000) = 77 
    [30.000, 32.500) = 8 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.475 ms/op
     p(50.0000) =      5.702 ms/op
     p(90.0000) =      7.209 ms/op
     p(95.0000) =      8.405 ms/op
     p(99.0000) =     11.780 ms/op
     p(99.9000) =     25.203 ms/op
     p(99.9900) =     29.364 ms/op
     p(99.9990) =     30.750 ms/op
     p(99.9999) =     30.867 ms/op
    p(100.0000) =     30.867 ms/op


# Run complete. Total time: 00:13:17

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   6.182 ± 4.264  ops/ms
ClientPb.existUser                       thrpt       3   6.327 ± 4.898  ops/ms
ClientPb.getUser                         thrpt       3   5.902 ± 5.047  ops/ms
ClientPb.listUser                        thrpt       3   5.049 ± 4.677  ops/ms
ClientPb.createUser                       avgt       3   5.463 ± 2.102   ms/op
ClientPb.existUser                        avgt       3   4.956 ± 2.643   ms/op
ClientPb.getUser                          avgt       3   5.198 ± 0.698   ms/op
ClientPb.listUser                         avgt       3   6.090 ± 0.368   ms/op
ClientPb.createUser                     sample  179024   5.359 ± 0.012   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.556           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.063           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.660           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.619           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.846           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.609           ms/op
ClientPb.createUser:createUser·p0.9999  sample          36.504           ms/op
ClientPb.createUser:createUser·p1.00    sample          38.076           ms/op
ClientPb.existUser                      sample  186591   5.142 ± 0.011   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.266           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.850           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.472           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.343           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.404           ms/op
ClientPb.existUser:existUser·p0.999     sample          16.545           ms/op
ClientPb.existUser:existUser·p0.9999    sample          31.480           ms/op
ClientPb.existUser:existUser·p1.00      sample          33.882           ms/op
ClientPb.getUser                        sample  176218   5.444 ± 0.013   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.978           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.079           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.898           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.339           ms/op
ClientPb.getUser:getUser·p0.99          sample          11.796           ms/op
ClientPb.getUser:getUser·p0.999         sample          22.581           ms/op
ClientPb.getUser:getUser·p0.9999        sample          31.109           ms/op
ClientPb.getUser:getUser·p1.00          sample          35.193           ms/op
ClientPb.listUser                       sample  159859   6.001 ± 0.013   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.475           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.702           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.209           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.405           ms/op
ClientPb.listUser:listUser·p0.99        sample          11.780           ms/op
ClientPb.listUser:listUser·p0.999       sample          25.203           ms/op
ClientPb.listUser:listUser·p0.9999      sample          29.364           ms/op
ClientPb.listUser:listUser·p1.00        sample          30.867           ms/op
