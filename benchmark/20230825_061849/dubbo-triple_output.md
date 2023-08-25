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
# Warmup Iteration   1: 1.240 ops/ms
# Warmup Iteration   2: 2.867 ops/ms
# Warmup Iteration   3: 6.128 ops/ms
Iteration   1: 6.363 ops/ms
Iteration   2: 6.647 ops/ms
Iteration   3: 6.284 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.431 ±(99.9%) 3.478 ops/ms [Average]
  (min, avg, max) = (6.284, 6.431, 6.647), stdev = 0.191
  CI (99.9%): [2.954, 9.909] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:11
# Fork: 1 of 1
# Warmup Iteration   1: 1.850 ops/ms
# Warmup Iteration   2: 5.590 ops/ms
# Warmup Iteration   3: 6.488 ops/ms
Iteration   1: 6.575 ops/ms
Iteration   2: 6.681 ops/ms
Iteration   3: 6.570 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.609 ±(99.9%) 1.147 ops/ms [Average]
  (min, avg, max) = (6.570, 6.609, 6.681), stdev = 0.063
  CI (99.9%): [5.462, 7.756] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:04
# Fork: 1 of 1
# Warmup Iteration   1: 1.893 ops/ms
# Warmup Iteration   2: 5.095 ops/ms
# Warmup Iteration   3: 6.050 ops/ms
Iteration   1: 6.303 ops/ms
Iteration   2: 6.146 ops/ms
Iteration   3: 6.248 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.232 ±(99.9%) 1.458 ops/ms [Average]
  (min, avg, max) = (6.146, 6.232, 6.303), stdev = 0.080
  CI (99.9%): [4.774, 7.690] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:58
# Fork: 1 of 1
# Warmup Iteration   1: 1.748 ops/ms
# Warmup Iteration   2: 4.114 ops/ms
# Warmup Iteration   3: 5.463 ops/ms
Iteration   1: 5.094 ops/ms
Iteration   2: 5.220 ops/ms
Iteration   3: 5.304 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.206 ±(99.9%) 1.926 ops/ms [Average]
  (min, avg, max) = (5.094, 5.206, 5.304), stdev = 0.106
  CI (99.9%): [3.280, 7.132] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:51
# Fork: 1 of 1
# Warmup Iteration   1: 16.668 ±(99.9%) 0.080 ms/op
# Warmup Iteration   2: 5.725 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 5.514 ±(99.9%) 0.008 ms/op
Iteration   1: 5.246 ±(99.9%) 0.010 ms/op
Iteration   2: 5.267 ±(99.9%) 0.010 ms/op
Iteration   3: 5.099 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.204 ±(99.9%) 1.664 ms/op [Average]
  (min, avg, max) = (5.099, 5.204, 5.267), stdev = 0.091
  CI (99.9%): [3.540, 6.868] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:45
# Fork: 1 of 1
# Warmup Iteration   1: 13.890 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 5.601 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 5.189 ±(99.9%) 0.005 ms/op
Iteration   1: 4.919 ±(99.9%) 0.008 ms/op
Iteration   2: 5.046 ±(99.9%) 0.009 ms/op
Iteration   3: 4.865 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.944 ±(99.9%) 1.697 ms/op [Average]
  (min, avg, max) = (4.865, 4.944, 5.046), stdev = 0.093
  CI (99.9%): [3.246, 6.641] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:38
# Fork: 1 of 1
# Warmup Iteration   1: 15.508 ±(99.9%) 0.093 ms/op
# Warmup Iteration   2: 6.486 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 5.186 ±(99.9%) 0.010 ms/op
Iteration   1: 5.331 ±(99.9%) 0.010 ms/op
Iteration   2: 5.320 ±(99.9%) 0.008 ms/op
Iteration   3: 5.027 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.226 ±(99.9%) 3.145 ms/op [Average]
  (min, avg, max) = (5.027, 5.226, 5.331), stdev = 0.172
  CI (99.9%): [2.080, 8.371] (assumes normal distribution)


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
# Warmup Iteration   1: 17.059 ±(99.9%) 0.070 ms/op
# Warmup Iteration   2: 6.950 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 6.193 ±(99.9%) 0.019 ms/op
Iteration   1: 6.115 ±(99.9%) 0.011 ms/op
Iteration   2: 5.749 ±(99.9%) 0.011 ms/op
Iteration   3: 5.911 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.925 ±(99.9%) 3.349 ms/op [Average]
  (min, avg, max) = (5.749, 5.925, 6.115), stdev = 0.184
  CI (99.9%): [2.576, 9.274] (assumes normal distribution)


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
# Warmup Iteration   1: 15.623 ±(99.9%) 0.219 ms/op
# Warmup Iteration   2: 6.554 ±(99.9%) 0.039 ms/op
# Warmup Iteration   3: 5.629 ±(99.9%) 0.024 ms/op
Iteration   1: 5.284 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   1.692 ms/op
                 createUser·p0.50:   4.940 ms/op
                 createUser·p0.90:   6.709 ms/op
                 createUser·p0.95:   7.627 ms/op
                 createUser·p0.99:   10.174 ms/op
                 createUser·p0.999:  25.226 ms/op
                 createUser·p0.9999: 28.728 ms/op
                 createUser·p1.00:   29.590 ms/op

Iteration   2: 5.150 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   1.442 ms/op
                 createUser·p0.50:   4.915 ms/op
                 createUser·p0.90:   6.201 ms/op
                 createUser·p0.95:   6.939 ms/op
                 createUser·p0.99:   9.355 ms/op
                 createUser·p0.999:  24.904 ms/op
                 createUser·p0.9999: 30.827 ms/op
                 createUser·p1.00:   31.818 ms/op

Iteration   3: 5.205 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   2.322 ms/op
                 createUser·p0.50:   4.940 ms/op
                 createUser·p0.90:   6.365 ms/op
                 createUser·p0.95:   6.955 ms/op
                 createUser·p0.99:   9.423 ms/op
                 createUser·p0.999:  28.164 ms/op
                 createUser·p0.9999: 35.062 ms/op
                 createUser·p1.00:   38.076 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 184255
  mean =      5.213 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20 
    [ 2.500,  5.000) = 99336 
    [ 5.000,  7.500) = 77363 
    [ 7.500, 10.000) = 5899 
    [10.000, 12.500) = 1007 
    [12.500, 15.000) = 314 
    [15.000, 17.500) = 65 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 78 
    [27.500, 30.000) = 89 
    [30.000, 32.500) = 27 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      1.442 ms/op
     p(50.0000) =      4.932 ms/op
     p(90.0000) =      6.414 ms/op
     p(95.0000) =      7.209 ms/op
     p(99.0000) =      9.748 ms/op
     p(99.9000) =     25.354 ms/op
     p(99.9900) =     30.891 ms/op
     p(99.9990) =     38.076 ms/op
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
# Warmup Iteration   1: 14.020 ±(99.9%) 0.212 ms/op
# Warmup Iteration   2: 5.721 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 5.318 ±(99.9%) 0.018 ms/op
Iteration   1: 5.035 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   2.171 ms/op
                 existUser·p0.50:   4.727 ms/op
                 existUser·p0.90:   6.291 ms/op
                 existUser·p0.95:   7.234 ms/op
                 existUser·p0.99:   9.878 ms/op
                 existUser·p0.999:  25.214 ms/op
                 existUser·p0.9999: 29.008 ms/op
                 existUser·p1.00:   29.524 ms/op

Iteration   2: 4.942 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   1.823 ms/op
                 existUser·p0.50:   4.719 ms/op
                 existUser·p0.90:   5.874 ms/op
                 existUser·p0.95:   6.480 ms/op
                 existUser·p0.99:   9.470 ms/op
                 existUser·p0.999:  19.540 ms/op
                 existUser·p0.9999: 31.850 ms/op
                 existUser·p1.00:   32.834 ms/op

Iteration   3: 5.117 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   2.126 ms/op
                 existUser·p0.50:   4.817 ms/op
                 existUser·p0.90:   6.242 ms/op
                 existUser·p0.95:   7.111 ms/op
                 existUser·p0.99:   10.584 ms/op
                 existUser·p0.999:  24.379 ms/op
                 existUser·p0.9999: 26.845 ms/op
                 existUser·p1.00:   27.263 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 190705
  mean =      5.030 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 50 
    [ 2.500,  5.000) = 121437 
    [ 5.000,  7.500) = 62577 
    [ 7.500, 10.000) = 4681 
    [10.000, 12.500) = 1187 
    [12.500, 15.000) = 431 
    [15.000, 17.500) = 92 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 63 
    [25.000, 27.500) = 81 
    [27.500, 30.000) = 38 
    [30.000, 32.500) = 18 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.823 ms/op
     p(50.0000) =      4.751 ms/op
     p(90.0000) =      6.119 ms/op
     p(95.0000) =      6.922 ms/op
     p(99.0000) =     10.060 ms/op
     p(99.9000) =     23.078 ms/op
     p(99.9900) =     30.044 ms/op
     p(99.9990) =     32.447 ms/op
     p(99.9999) =     32.834 ms/op
    p(100.0000) =     32.834 ms/op


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
# Warmup Iteration   1: 14.805 ±(99.9%) 0.236 ms/op
# Warmup Iteration   2: 5.630 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 5.311 ±(99.9%) 0.021 ms/op
Iteration   1: 4.908 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   2.351 ms/op
                 getUser·p0.50:   4.669 ms/op
                 getUser·p0.90:   5.857 ms/op
                 getUser·p0.95:   6.816 ms/op
                 getUser·p0.99:   9.348 ms/op
                 getUser·p0.999:  15.183 ms/op
                 getUser·p0.9999: 25.247 ms/op
                 getUser·p1.00:   25.362 ms/op

Iteration   2: 5.482 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   1.993 ms/op
                 getUser·p0.50:   5.112 ms/op
                 getUser·p0.90:   6.947 ms/op
                 getUser·p0.95:   8.167 ms/op
                 getUser·p0.99:   10.928 ms/op
                 getUser·p0.999:  27.165 ms/op
                 getUser·p0.9999: 42.992 ms/op
                 getUser·p1.00:   43.319 ms/op

Iteration   3: 5.465 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   2.568 ms/op
                 getUser·p0.50:   5.136 ms/op
                 getUser·p0.90:   6.865 ms/op
                 getUser·p0.95:   8.102 ms/op
                 getUser·p0.99:   10.551 ms/op
                 getUser·p0.999:  27.932 ms/op
                 getUser·p0.9999: 32.225 ms/op
                 getUser·p1.00:   33.227 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 182123
  mean =      5.271 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 95771 
    [ 5.000, 10.000) = 84051 
    [10.000, 15.000) = 1948 
    [15.000, 20.000) = 124 
    [20.000, 25.000) = 70 
    [25.000, 30.000) = 100 
    [30.000, 35.000) = 38 
    [35.000, 40.000) = 13 
    [40.000, 45.000) = 8 

  Percentiles, ms/op:
      p(0.0000) =      1.993 ms/op
     p(50.0000) =      4.956 ms/op
     p(90.0000) =      6.562 ms/op
     p(95.0000) =      7.758 ms/op
     p(99.0000) =     10.437 ms/op
     p(99.9000) =     23.462 ms/op
     p(99.9900) =     36.504 ms/op
     p(99.9990) =     43.212 ms/op
     p(99.9999) =     43.319 ms/op
    p(100.0000) =     43.319 ms/op


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
# Warmup Iteration   1: 17.744 ±(99.9%) 0.276 ms/op
# Warmup Iteration   2: 6.793 ±(99.9%) 0.034 ms/op
# Warmup Iteration   3: 6.153 ±(99.9%) 0.026 ms/op
Iteration   1: 5.921 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   1.765 ms/op
                 listUser·p0.50:   5.587 ms/op
                 listUser·p0.90:   7.070 ms/op
                 listUser·p0.95:   8.471 ms/op
                 listUser·p0.99:   11.466 ms/op
                 listUser·p0.999:  25.919 ms/op
                 listUser·p0.9999: 31.202 ms/op
                 listUser·p1.00:   31.850 ms/op

Iteration   2: 5.942 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   2.806 ms/op
                 listUser·p0.50:   5.628 ms/op
                 listUser·p0.90:   7.037 ms/op
                 listUser·p0.95:   7.979 ms/op
                 listUser·p0.99:   11.199 ms/op
                 listUser·p0.999:  27.429 ms/op
                 listUser·p0.9999: 30.166 ms/op
                 listUser·p1.00:   30.474 ms/op

Iteration   3: 5.895 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   2.806 ms/op
                 listUser·p0.50:   5.571 ms/op
                 listUser·p0.90:   6.971 ms/op
                 listUser·p0.95:   8.225 ms/op
                 listUser·p0.99:   11.272 ms/op
                 listUser·p0.999:  20.276 ms/op
                 listUser·p0.9999: 21.973 ms/op
                 listUser·p1.00:   22.839 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 162185
  mean =      5.919 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3 
    [ 2.500,  5.000) = 20854 
    [ 5.000,  7.500) = 129891 
    [ 7.500, 10.000) = 8180 
    [10.000, 12.500) = 2199 
    [12.500, 15.000) = 570 
    [15.000, 17.500) = 151 
    [17.500, 20.000) = 55 
    [20.000, 22.500) = 68 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 101 
    [27.500, 30.000) = 64 
    [30.000, 32.500) = 23 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.765 ms/op
     p(50.0000) =      5.595 ms/op
     p(90.0000) =      7.021 ms/op
     p(95.0000) =      8.208 ms/op
     p(99.0000) =     11.321 ms/op
     p(99.9000) =     25.842 ms/op
     p(99.9900) =     30.315 ms/op
     p(99.9990) =     31.728 ms/op
     p(99.9999) =     31.850 ms/op
    p(100.0000) =     31.850 ms/op


# Run complete. Total time: 00:13:16

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   6.431 ± 3.478  ops/ms
ClientPb.existUser                       thrpt       3   6.609 ± 1.147  ops/ms
ClientPb.getUser                         thrpt       3   6.232 ± 1.458  ops/ms
ClientPb.listUser                        thrpt       3   5.206 ± 1.926  ops/ms
ClientPb.createUser                       avgt       3   5.204 ± 1.664   ms/op
ClientPb.existUser                        avgt       3   4.944 ± 1.697   ms/op
ClientPb.getUser                          avgt       3   5.226 ± 3.145   ms/op
ClientPb.listUser                         avgt       3   5.925 ± 3.349   ms/op
ClientPb.createUser                     sample  184255   5.213 ± 0.011   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.442           ms/op
ClientPb.createUser:createUser·p0.50    sample           4.932           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.414           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.209           ms/op
ClientPb.createUser:createUser·p0.99    sample           9.748           ms/op
ClientPb.createUser:createUser·p0.999   sample          25.354           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.891           ms/op
ClientPb.createUser:createUser·p1.00    sample          38.076           ms/op
ClientPb.existUser                      sample  190705   5.030 ± 0.010   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.823           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.751           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.119           ms/op
ClientPb.existUser:existUser·p0.95      sample           6.922           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.060           ms/op
ClientPb.existUser:existUser·p0.999     sample          23.078           ms/op
ClientPb.existUser:existUser·p0.9999    sample          30.044           ms/op
ClientPb.existUser:existUser·p1.00      sample          32.834           ms/op
ClientPb.getUser                        sample  182123   5.271 ± 0.012   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.993           ms/op
ClientPb.getUser:getUser·p0.50          sample           4.956           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.562           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.758           ms/op
ClientPb.getUser:getUser·p0.99          sample          10.437           ms/op
ClientPb.getUser:getUser·p0.999         sample          23.462           ms/op
ClientPb.getUser:getUser·p0.9999        sample          36.504           ms/op
ClientPb.getUser:getUser·p1.00          sample          43.319           ms/op
ClientPb.listUser                       sample  162185   5.919 ± 0.012   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.765           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.595           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.021           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.208           ms/op
ClientPb.listUser:listUser·p0.99        sample          11.321           ms/op
ClientPb.listUser:listUser·p0.999       sample          25.842           ms/op
ClientPb.listUser:listUser·p0.9999      sample          30.315           ms/op
ClientPb.listUser:listUser·p1.00        sample          31.850           ms/op
