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
# Warmup Iteration   1: 1.684 ops/ms
# Warmup Iteration   2: 3.618 ops/ms
# Warmup Iteration   3: 7.084 ops/ms
Iteration   1: 7.510 ops/ms
Iteration   2: 7.568 ops/ms
Iteration   3: 8.167 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.749 ±(99.9%) 6.636 ops/ms [Average]
  (min, avg, max) = (7.510, 7.749, 8.167), stdev = 0.364
  CI (99.9%): [1.113, 14.384] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:12
# Fork: 1 of 1
# Warmup Iteration   1: 2.314 ops/ms
# Warmup Iteration   2: 6.403 ops/ms
# Warmup Iteration   3: 8.249 ops/ms
Iteration   1: 8.268 ops/ms
Iteration   2: 8.144 ops/ms
Iteration   3: 7.797 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.070 ±(99.9%) 4.452 ops/ms [Average]
  (min, avg, max) = (7.797, 8.070, 8.268), stdev = 0.244
  CI (99.9%): [3.618, 12.522] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.228 ops/ms
# Warmup Iteration   2: 6.332 ops/ms
# Warmup Iteration   3: 7.571 ops/ms
Iteration   1: 7.518 ops/ms
Iteration   2: 7.506 ops/ms
Iteration   3: 8.086 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.703 ±(99.9%) 6.045 ops/ms [Average]
  (min, avg, max) = (7.506, 7.703, 8.086), stdev = 0.331
  CI (99.9%): [1.659, 13.748] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 2.107 ops/ms
# Warmup Iteration   2: 4.872 ops/ms
# Warmup Iteration   3: 6.339 ops/ms
Iteration   1: 6.789 ops/ms
Iteration   2: 6.532 ops/ms
Iteration   3: 6.956 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.759 ±(99.9%) 3.901 ops/ms [Average]
  (min, avg, max) = (6.532, 6.759, 6.956), stdev = 0.214
  CI (99.9%): [2.858, 10.660] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:50
# Fork: 1 of 1
# Warmup Iteration   1: 14.135 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 5.210 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.509 ±(99.9%) 0.008 ms/op
Iteration   1: 4.304 ±(99.9%) 0.006 ms/op
Iteration   2: 4.142 ±(99.9%) 0.006 ms/op
Iteration   3: 4.316 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.254 ±(99.9%) 1.774 ms/op [Average]
  (min, avg, max) = (4.142, 4.254, 4.316), stdev = 0.097
  CI (99.9%): [2.480, 6.028] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:44
# Fork: 1 of 1
# Warmup Iteration   1: 12.480 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 4.740 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.110 ±(99.9%) 0.006 ms/op
Iteration   1: 4.127 ±(99.9%) 0.004 ms/op
Iteration   2: 4.074 ±(99.9%) 0.005 ms/op
Iteration   3: 3.840 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.014 ±(99.9%) 2.784 ms/op [Average]
  (min, avg, max) = (3.840, 4.014, 4.127), stdev = 0.153
  CI (99.9%): [1.230, 6.798] (assumes normal distribution)


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
# Warmup Iteration   1: 13.175 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 4.692 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.161 ±(99.9%) 0.005 ms/op
Iteration   1: 4.186 ±(99.9%) 0.006 ms/op
Iteration   2: 4.227 ±(99.9%) 0.008 ms/op
Iteration   3: 4.115 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.176 ±(99.9%) 1.032 ms/op [Average]
  (min, avg, max) = (4.115, 4.176, 4.227), stdev = 0.057
  CI (99.9%): [3.144, 5.208] (assumes normal distribution)


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
# Warmup Iteration   1: 14.543 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 5.523 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.762 ±(99.9%) 0.012 ms/op
Iteration   1: 4.787 ±(99.9%) 0.008 ms/op
Iteration   2: 4.795 ±(99.9%) 0.010 ms/op
Iteration   3: 4.673 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.752 ±(99.9%) 1.241 ms/op [Average]
  (min, avg, max) = (4.673, 4.752, 4.795), stdev = 0.068
  CI (99.9%): [3.510, 5.993] (assumes normal distribution)


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
# Warmup Iteration   1: 12.835 ±(99.9%) 0.173 ms/op
# Warmup Iteration   2: 5.765 ±(99.9%) 0.033 ms/op
# Warmup Iteration   3: 4.548 ±(99.9%) 0.018 ms/op
Iteration   1: 4.271 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.874 ms/op
                 createUser·p0.50:   4.006 ms/op
                 createUser·p0.90:   5.071 ms/op
                 createUser·p0.95:   5.915 ms/op
                 createUser·p0.99:   8.618 ms/op
                 createUser·p0.999:  12.882 ms/op
                 createUser·p0.9999: 26.611 ms/op
                 createUser·p1.00:   28.508 ms/op

Iteration   2: 4.119 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.522 ms/op
                 createUser·p0.50:   3.936 ms/op
                 createUser·p0.90:   4.678 ms/op
                 createUser·p0.95:   5.751 ms/op
                 createUser·p0.99:   8.315 ms/op
                 createUser·p0.999:  26.247 ms/op
                 createUser·p0.9999: 33.751 ms/op
                 createUser·p1.00:   34.537 ms/op

Iteration   3: 4.203 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.489 ms/op
                 createUser·p0.50:   4.018 ms/op
                 createUser·p0.90:   4.891 ms/op
                 createUser·p0.95:   5.284 ms/op
                 createUser·p0.99:   7.799 ms/op
                 createUser·p0.999:  29.719 ms/op
                 createUser·p0.9999: 34.039 ms/op
                 createUser·p1.00:   34.341 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 228581
  mean =      4.197 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 181 
    [ 2.500,  5.000) = 208169 
    [ 5.000,  7.500) = 16709 
    [ 7.500, 10.000) = 2402 
    [10.000, 12.500) = 716 
    [12.500, 15.000) = 124 
    [15.000, 17.500) = 23 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 83 
    [27.500, 30.000) = 65 
    [30.000, 32.500) = 46 
    [32.500, 35.000) = 35 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.489 ms/op
     p(50.0000) =      3.981 ms/op
     p(90.0000) =      4.915 ms/op
     p(95.0000) =      5.636 ms/op
     p(99.0000) =      8.274 ms/op
     p(99.9000) =     25.002 ms/op
     p(99.9900) =     33.498 ms/op
     p(99.9990) =     34.434 ms/op
     p(99.9999) =     34.537 ms/op
    p(100.0000) =     34.537 ms/op


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
# Warmup Iteration   1: 10.858 ±(99.9%) 0.151 ms/op
# Warmup Iteration   2: 4.548 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.073 ±(99.9%) 0.014 ms/op
Iteration   1: 4.154 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   1.935 ms/op
                 existUser·p0.50:   3.867 ms/op
                 existUser·p0.90:   5.022 ms/op
                 existUser·p0.95:   6.242 ms/op
                 existUser·p0.99:   8.520 ms/op
                 existUser·p0.999:  23.590 ms/op
                 existUser·p0.9999: 28.041 ms/op
                 existUser·p1.00:   29.491 ms/op

Iteration   2: 3.949 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.737 ms/op
                 existUser·p0.50:   3.744 ms/op
                 existUser·p0.90:   4.432 ms/op
                 existUser·p0.95:   5.202 ms/op
                 existUser·p0.99:   7.672 ms/op
                 existUser·p0.999:  11.730 ms/op
                 existUser·p0.9999: 28.606 ms/op
                 existUser·p1.00:   29.131 ms/op

Iteration   3: 4.187 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   1.913 ms/op
                 existUser·p0.50:   3.932 ms/op
                 existUser·p0.90:   4.940 ms/op
                 existUser·p0.95:   6.324 ms/op
                 existUser·p0.99:   9.060 ms/op
                 existUser·p0.999:  22.118 ms/op
                 existUser·p0.9999: 42.777 ms/op
                 existUser·p1.00:   44.630 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 234495
  mean =      4.094 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 214738 
    [ 5.000, 10.000) = 18737 
    [10.000, 15.000) = 703 
    [15.000, 20.000) = 61 
    [20.000, 25.000) = 95 
    [25.000, 30.000) = 97 
    [30.000, 35.000) = 32 
    [35.000, 40.000) = 9 
    [40.000, 45.000) = 23 

  Percentiles, ms/op:
      p(0.0000) =      1.737 ms/op
     p(50.0000) =      3.863 ms/op
     p(90.0000) =      4.792 ms/op
     p(95.0000) =      5.964 ms/op
     p(99.0000) =      8.487 ms/op
     p(99.9000) =     22.348 ms/op
     p(99.9900) =     40.033 ms/op
     p(99.9990) =     44.585 ms/op
     p(99.9999) =     44.630 ms/op
    p(100.0000) =     44.630 ms/op


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
# Warmup Iteration   1: 13.080 ±(99.9%) 0.171 ms/op
# Warmup Iteration   2: 4.866 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.483 ±(99.9%) 0.018 ms/op
Iteration   1: 4.305 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   2.095 ms/op
                 getUser·p0.50:   4.047 ms/op
                 getUser·p0.90:   5.063 ms/op
                 getUser·p0.95:   6.201 ms/op
                 getUser·p0.99:   8.635 ms/op
                 getUser·p0.999:  18.383 ms/op
                 getUser·p0.9999: 26.870 ms/op
                 getUser·p1.00:   27.263 ms/op

Iteration   2: 4.346 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   1.335 ms/op
                 getUser·p0.50:   4.026 ms/op
                 getUser·p0.90:   5.333 ms/op
                 getUser·p0.95:   6.504 ms/op
                 getUser·p0.99:   9.847 ms/op
                 getUser·p0.999:  29.407 ms/op
                 getUser·p0.9999: 34.341 ms/op
                 getUser·p1.00:   35.127 ms/op

Iteration   3: 4.301 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   2.025 ms/op
                 getUser·p0.50:   4.051 ms/op
                 getUser·p0.90:   5.022 ms/op
                 getUser·p0.95:   6.111 ms/op
                 getUser·p0.99:   8.602 ms/op
                 getUser·p0.999:  13.255 ms/op
                 getUser·p0.9999: 41.128 ms/op
                 getUser·p1.00:   41.878 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 222295
  mean =      4.317 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 197601 
    [ 5.000, 10.000) = 23160 
    [10.000, 15.000) = 1267 
    [15.000, 20.000) = 41 
    [20.000, 25.000) = 26 
    [25.000, 30.000) = 71 
    [30.000, 35.000) = 63 
    [35.000, 40.000) = 42 
    [40.000, 45.000) = 24 

  Percentiles, ms/op:
      p(0.0000) =      1.335 ms/op
     p(50.0000) =      4.039 ms/op
     p(90.0000) =      5.120 ms/op
     p(95.0000) =      6.291 ms/op
     p(99.0000) =      9.060 ms/op
     p(99.9000) =     24.373 ms/op
     p(99.9900) =     40.108 ms/op
     p(99.9990) =     41.746 ms/op
     p(99.9999) =     41.878 ms/op
    p(100.0000) =     41.878 ms/op


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
# Warmup Iteration   1: 15.785 ±(99.9%) 0.232 ms/op
# Warmup Iteration   2: 5.729 ±(99.9%) 0.031 ms/op
# Warmup Iteration   3: 5.242 ±(99.9%) 0.022 ms/op
Iteration   1: 4.897 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.714 ms/op
                 listUser·p0.50:   4.530 ms/op
                 listUser·p0.90:   5.612 ms/op
                 listUser·p0.95:   7.291 ms/op
                 listUser·p0.99:   10.355 ms/op
                 listUser·p0.999:  25.779 ms/op
                 listUser·p0.9999: 29.998 ms/op
                 listUser·p1.00:   30.999 ms/op

Iteration   2: 4.835 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.942 ms/op
                 listUser·p0.50:   4.555 ms/op
                 listUser·p0.90:   5.480 ms/op
                 listUser·p0.95:   6.193 ms/op
                 listUser·p0.99:   9.355 ms/op
                 listUser·p0.999:  19.229 ms/op
                 listUser·p0.9999: 25.768 ms/op
                 listUser·p1.00:   26.116 ms/op

Iteration   3: 4.901 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   2.286 ms/op
                 listUser·p0.50:   4.612 ms/op
                 listUser·p0.90:   5.489 ms/op
                 listUser·p0.95:   6.857 ms/op
                 listUser·p0.99:   10.043 ms/op
                 listUser·p0.999:  18.514 ms/op
                 listUser·p0.9999: 20.677 ms/op
                 listUser·p1.00:   20.742 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 196702
  mean =      4.877 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13 
    [ 2.500,  5.000) = 154381 
    [ 5.000,  7.500) = 34614 
    [ 7.500, 10.000) = 5681 
    [10.000, 12.500) = 1163 
    [12.500, 15.000) = 369 
    [15.000, 17.500) = 135 
    [17.500, 20.000) = 104 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 92 
    [25.000, 27.500) = 84 
    [27.500, 30.000) = 28 
    [30.000, 32.500) = 6 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.714 ms/op
     p(50.0000) =      4.563 ms/op
     p(90.0000) =      5.513 ms/op
     p(95.0000) =      6.734 ms/op
     p(99.0000) =     10.076 ms/op
     p(99.9000) =     22.970 ms/op
     p(99.9900) =     28.082 ms/op
     p(99.9990) =     30.270 ms/op
     p(99.9999) =     30.999 ms/op
    p(100.0000) =     30.999 ms/op


# Run complete. Total time: 00:13:17

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.749 ± 6.636  ops/ms
ClientPb.existUser                       thrpt       3   8.070 ± 4.452  ops/ms
ClientPb.getUser                         thrpt       3   7.703 ± 6.045  ops/ms
ClientPb.listUser                        thrpt       3   6.759 ± 3.901  ops/ms
ClientPb.createUser                       avgt       3   4.254 ± 1.774   ms/op
ClientPb.existUser                        avgt       3   4.014 ± 2.784   ms/op
ClientPb.getUser                          avgt       3   4.176 ± 1.032   ms/op
ClientPb.listUser                         avgt       3   4.752 ± 1.241   ms/op
ClientPb.createUser                     sample  228581   4.197 ± 0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.489           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.981           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.915           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.636           ms/op
ClientPb.createUser:createUser·p0.99    sample           8.274           ms/op
ClientPb.createUser:createUser·p0.999   sample          25.002           ms/op
ClientPb.createUser:createUser·p0.9999  sample          33.498           ms/op
ClientPb.createUser:createUser·p1.00    sample          34.537           ms/op
ClientPb.existUser                      sample  234495   4.094 ± 0.009   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.737           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.863           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.792           ms/op
ClientPb.existUser:existUser·p0.95      sample           5.964           ms/op
ClientPb.existUser:existUser·p0.99      sample           8.487           ms/op
ClientPb.existUser:existUser·p0.999     sample          22.348           ms/op
ClientPb.existUser:existUser·p0.9999    sample          40.033           ms/op
ClientPb.existUser:existUser·p1.00      sample          44.630           ms/op
ClientPb.getUser                        sample  222295   4.317 ± 0.010   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.335           ms/op
ClientPb.getUser:getUser·p0.50          sample           4.039           ms/op
ClientPb.getUser:getUser·p0.90          sample           5.120           ms/op
ClientPb.getUser:getUser·p0.95          sample           6.291           ms/op
ClientPb.getUser:getUser·p0.99          sample           9.060           ms/op
ClientPb.getUser:getUser·p0.999         sample          24.373           ms/op
ClientPb.getUser:getUser·p0.9999        sample          40.108           ms/op
ClientPb.getUser:getUser·p1.00          sample          41.878           ms/op
ClientPb.listUser                       sample  196702   4.877 ± 0.010   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.714           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.563           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.513           ms/op
ClientPb.listUser:listUser·p0.95        sample           6.734           ms/op
ClientPb.listUser:listUser·p0.99        sample          10.076           ms/op
ClientPb.listUser:listUser·p0.999       sample          22.970           ms/op
ClientPb.listUser:listUser·p0.9999      sample          28.082           ms/op
ClientPb.listUser:listUser·p1.00        sample          30.999           ms/op
