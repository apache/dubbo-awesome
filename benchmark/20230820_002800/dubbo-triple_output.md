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
# Warmup Iteration   1: 2.184 ops/ms
# Warmup Iteration   2: 5.809 ops/ms
# Warmup Iteration   3: 8.409 ops/ms
Iteration   1: 8.949 ops/ms
Iteration   2: 9.069 ops/ms
Iteration   3: 8.912 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.977 ±(99.9%) 1.491 ops/ms [Average]
  (min, avg, max) = (8.912, 8.977, 9.069), stdev = 0.082
  CI (99.9%): [7.486, 10.468] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 3.640 ops/ms
# Warmup Iteration   2: 8.391 ops/ms
# Warmup Iteration   3: 9.130 ops/ms
Iteration   1: 9.561 ops/ms
Iteration   2: 9.408 ops/ms
Iteration   3: 9.229 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.399 ±(99.9%) 3.031 ops/ms [Average]
  (min, avg, max) = (9.229, 9.399, 9.561), stdev = 0.166
  CI (99.9%): [6.368, 12.430] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 2.447 ops/ms
# Warmup Iteration   2: 7.772 ops/ms
# Warmup Iteration   3: 8.929 ops/ms
Iteration   1: 8.899 ops/ms
Iteration   2: 9.298 ops/ms
Iteration   3: 9.086 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.094 ±(99.9%) 3.645 ops/ms [Average]
  (min, avg, max) = (8.899, 9.094, 9.298), stdev = 0.200
  CI (99.9%): [5.449, 12.740] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.307 ops/ms
# Warmup Iteration   2: 6.951 ops/ms
# Warmup Iteration   3: 7.710 ops/ms
Iteration   1: 7.762 ops/ms
Iteration   2: 8.083 ops/ms
Iteration   3: 7.750 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.865 ±(99.9%) 3.439 ops/ms [Average]
  (min, avg, max) = (7.750, 7.865, 8.083), stdev = 0.189
  CI (99.9%): [4.426, 11.304] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 10.809 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 4.065 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.805 ±(99.9%) 0.005 ms/op
Iteration   1: 3.578 ±(99.9%) 0.008 ms/op
Iteration   2: 3.516 ±(99.9%) 0.008 ms/op
Iteration   3: 3.464 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.519 ±(99.9%) 1.042 ms/op [Average]
  (min, avg, max) = (3.464, 3.519, 3.578), stdev = 0.057
  CI (99.9%): [2.478, 4.561] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 9.349 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.584 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.597 ±(99.9%) 0.005 ms/op
Iteration   1: 3.409 ±(99.9%) 0.008 ms/op
Iteration   2: 3.402 ±(99.9%) 0.006 ms/op
Iteration   3: 3.397 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.402 ±(99.9%) 0.111 ms/op [Average]
  (min, avg, max) = (3.397, 3.402, 3.409), stdev = 0.006
  CI (99.9%): [3.291, 3.514] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 10.009 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.897 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.626 ±(99.9%) 0.005 ms/op
Iteration   1: 3.482 ±(99.9%) 0.008 ms/op
Iteration   2: 3.486 ±(99.9%) 0.005 ms/op
Iteration   3: 3.431 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.466 ±(99.9%) 0.561 ms/op [Average]
  (min, avg, max) = (3.431, 3.466, 3.486), stdev = 0.031
  CI (99.9%): [2.905, 4.027] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 11.219 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 4.484 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.182 ±(99.9%) 0.007 ms/op
Iteration   1: 4.079 ±(99.9%) 0.007 ms/op
Iteration   2: 3.990 ±(99.9%) 0.011 ms/op
Iteration   3: 4.087 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.052 ±(99.9%) 0.985 ms/op [Average]
  (min, avg, max) = (3.990, 4.052, 4.087), stdev = 0.054
  CI (99.9%): [3.067, 5.037] (assumes normal distribution)


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
# Warmup Iteration   1: 9.552 ±(99.9%) 0.128 ms/op
# Warmup Iteration   2: 4.211 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 3.577 ±(99.9%) 0.011 ms/op
Iteration   1: 3.609 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.444 ms/op
                 createUser·p0.50:   3.473 ms/op
                 createUser·p0.90:   4.235 ms/op
                 createUser·p0.95:   4.571 ms/op
                 createUser·p0.99:   6.685 ms/op
                 createUser·p0.999:  23.409 ms/op
                 createUser·p0.9999: 25.442 ms/op
                 createUser·p1.00:   26.608 ms/op

Iteration   2: 3.573 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.329 ms/op
                 createUser·p0.50:   3.404 ms/op
                 createUser·p0.90:   4.182 ms/op
                 createUser·p0.95:   4.456 ms/op
                 createUser·p0.99:   6.324 ms/op
                 createUser·p0.999:  26.034 ms/op
                 createUser·p0.9999: 28.674 ms/op
                 createUser·p1.00:   30.147 ms/op

Iteration   3: 3.545 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.593 ms/op
                 createUser·p0.50:   3.359 ms/op
                 createUser·p0.90:   4.014 ms/op
                 createUser·p0.95:   4.415 ms/op
                 createUser·p0.99:   6.734 ms/op
                 createUser·p0.999:  19.280 ms/op
                 createUser·p0.9999: 30.244 ms/op
                 createUser·p1.00:   31.490 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 268313
  mean =      3.575 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4860 
    [ 2.500,  5.000) = 254414 
    [ 5.000,  7.500) = 7369 
    [ 7.500, 10.000) = 1123 
    [10.000, 12.500) = 145 
    [12.500, 15.000) = 114 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 63 
    [25.000, 27.500) = 131 
    [27.500, 30.000) = 40 
    [30.000, 32.500) = 16 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.329 ms/op
     p(50.0000) =      3.428 ms/op
     p(90.0000) =      4.157 ms/op
     p(95.0000) =      4.506 ms/op
     p(99.0000) =      6.545 ms/op
     p(99.9000) =     20.502 ms/op
     p(99.9900) =     28.934 ms/op
     p(99.9990) =     31.457 ms/op
     p(99.9999) =     31.490 ms/op
    p(100.0000) =     31.490 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.780 ±(99.9%) 0.097 ms/op
# Warmup Iteration   2: 3.642 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.471 ±(99.9%) 0.009 ms/op
Iteration   1: 3.423 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.192 ms/op
                 existUser·p0.50:   3.322 ms/op
                 existUser·p0.90:   3.871 ms/op
                 existUser·p0.95:   4.366 ms/op
                 existUser·p0.99:   6.111 ms/op
                 existUser·p0.999:  20.807 ms/op
                 existUser·p0.9999: 25.380 ms/op
                 existUser·p1.00:   27.558 ms/op

Iteration   2: 3.357 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.516 ms/op
                 existUser·p0.50:   3.310 ms/op
                 existUser·p0.90:   3.674 ms/op
                 existUser·p0.95:   3.990 ms/op
                 existUser·p0.99:   5.775 ms/op
                 existUser·p0.999:  23.843 ms/op
                 existUser·p0.9999: 27.934 ms/op
                 existUser·p1.00:   28.246 ms/op

Iteration   3: 3.438 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.417 ms/op
                 existUser·p0.50:   3.252 ms/op
                 existUser·p0.90:   3.908 ms/op
                 existUser·p0.95:   4.415 ms/op
                 existUser·p0.99:   6.885 ms/op
                 existUser·p0.999:  10.696 ms/op
                 existUser·p0.9999: 30.946 ms/op
                 existUser·p1.00:   32.276 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 281932
  mean =      3.405 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15314 
    [ 2.500,  5.000) = 257964 
    [ 5.000,  7.500) = 7343 
    [ 7.500, 10.000) = 906 
    [10.000, 12.500) = 128 
    [12.500, 15.000) = 21 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 85 
    [25.000, 27.500) = 95 
    [27.500, 30.000) = 25 
    [30.000, 32.500) = 24 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.192 ms/op
     p(50.0000) =      3.305 ms/op
     p(90.0000) =      3.813 ms/op
     p(95.0000) =      4.260 ms/op
     p(99.0000) =      6.242 ms/op
     p(99.9000) =     11.667 ms/op
     p(99.9900) =     29.872 ms/op
     p(99.9990) =     31.981 ms/op
     p(99.9999) =     32.276 ms/op
    p(100.0000) =     32.276 ms/op


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
# Warmup Iteration   1: 10.197 ±(99.9%) 0.134 ms/op
# Warmup Iteration   2: 4.214 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 3.628 ±(99.9%) 0.011 ms/op
Iteration   1: 3.571 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.053 ms/op
                 getUser·p0.50:   3.351 ms/op
                 getUser·p0.90:   3.932 ms/op
                 getUser·p0.95:   4.678 ms/op
                 getUser·p0.99:   7.561 ms/op
                 getUser·p0.999:  22.527 ms/op
                 getUser·p0.9999: 27.230 ms/op
                 getUser·p1.00:   31.457 ms/op

Iteration   2: 3.568 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.343 ms/op
                 getUser·p0.50:   3.330 ms/op
                 getUser·p0.90:   4.276 ms/op
                 getUser·p0.95:   4.989 ms/op
                 getUser·p0.99:   7.143 ms/op
                 getUser·p0.999:  23.233 ms/op
                 getUser·p0.9999: 24.936 ms/op
                 getUser·p1.00:   25.330 ms/op

Iteration   3: 3.492 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.968 ms/op
                 getUser·p0.50:   3.322 ms/op
                 getUser·p0.90:   3.830 ms/op
                 getUser·p0.95:   4.186 ms/op
                 getUser·p0.99:   6.881 ms/op
                 getUser·p0.999:  21.608 ms/op
                 getUser·p0.9999: 28.475 ms/op
                 getUser·p1.00:   30.704 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 270732
  mean =      3.543 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2479 
    [ 2.500,  5.000) = 256873 
    [ 5.000,  7.500) = 8984 
    [ 7.500, 10.000) = 1712 
    [10.000, 12.500) = 252 
    [12.500, 15.000) = 111 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 63 
    [22.500, 25.000) = 164 
    [25.000, 27.500) = 63 
    [27.500, 30.000) = 27 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.968 ms/op
     p(50.0000) =      3.334 ms/op
     p(90.0000) =      3.990 ms/op
     p(95.0000) =      4.792 ms/op
     p(99.0000) =      7.274 ms/op
     p(99.9000) =     22.315 ms/op
     p(99.9900) =     27.918 ms/op
     p(99.9990) =     30.886 ms/op
     p(99.9999) =     31.457 ms/op
    p(100.0000) =     31.457 ms/op


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
# Warmup Iteration   1: 12.266 ±(99.9%) 0.177 ms/op
# Warmup Iteration   2: 4.666 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.219 ±(99.9%) 0.015 ms/op
Iteration   1: 4.309 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.464 ms/op
                 listUser·p0.50:   4.108 ms/op
                 listUser·p0.90:   4.645 ms/op
                 listUser·p0.95:   5.579 ms/op
                 listUser·p0.99:   8.798 ms/op
                 listUser·p0.999:  23.783 ms/op
                 listUser·p0.9999: 34.210 ms/op
                 listUser·p1.00:   34.996 ms/op

Iteration   2: 4.159 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.310 ms/op
                 listUser·p0.50:   4.010 ms/op
                 listUser·p0.90:   4.514 ms/op
                 listUser·p0.95:   4.817 ms/op
                 listUser·p0.99:   7.998 ms/op
                 listUser·p0.999:  16.714 ms/op
                 listUser·p0.9999: 20.709 ms/op
                 listUser·p1.00:   20.742 ms/op

Iteration   3: 4.061 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.860 ms/op
                 listUser·p0.50:   3.936 ms/op
                 listUser·p0.90:   4.530 ms/op
                 listUser·p0.95:   4.940 ms/op
                 listUser·p0.99:   7.930 ms/op
                 listUser·p0.999:  14.795 ms/op
                 listUser·p0.9999: 19.988 ms/op
                 listUser·p1.00:   20.152 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 229797
  mean =      4.174 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 35 
    [ 2.500,  5.000) = 218161 
    [ 5.000,  7.500) = 8293 
    [ 7.500, 10.000) = 2155 
    [10.000, 12.500) = 549 
    [12.500, 15.000) = 243 
    [15.000, 17.500) = 105 
    [17.500, 20.000) = 77 
    [20.000, 22.500) = 52 
    [22.500, 25.000) = 79 
    [25.000, 27.500) = 16 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 32 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.464 ms/op
     p(50.0000) =      3.985 ms/op
     p(90.0000) =      4.563 ms/op
     p(95.0000) =      5.014 ms/op
     p(99.0000) =      8.307 ms/op
     p(99.9000) =     18.560 ms/op
     p(99.9900) =     33.561 ms/op
     p(99.9990) =     34.931 ms/op
     p(99.9999) =     34.996 ms/op
    p(100.0000) =     34.996 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.977 ± 1.491  ops/ms
ClientPb.existUser                       thrpt       3   9.399 ± 3.031  ops/ms
ClientPb.getUser                         thrpt       3   9.094 ± 3.645  ops/ms
ClientPb.listUser                        thrpt       3   7.865 ± 3.439  ops/ms
ClientPb.createUser                       avgt       3   3.519 ± 1.042   ms/op
ClientPb.existUser                        avgt       3   3.402 ± 0.111   ms/op
ClientPb.getUser                          avgt       3   3.466 ± 0.561   ms/op
ClientPb.listUser                         avgt       3   4.052 ± 0.985   ms/op
ClientPb.createUser                     sample  268313   3.575 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.329           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.428           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.157           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.506           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.545           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.502           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.934           ms/op
ClientPb.createUser:createUser·p1.00    sample          31.490           ms/op
ClientPb.existUser                      sample  281932   3.405 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.192           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.305           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.813           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.260           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.242           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.667           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.872           ms/op
ClientPb.existUser:existUser·p1.00      sample          32.276           ms/op
ClientPb.getUser                        sample  270732   3.543 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.968           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.334           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.990           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.792           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.274           ms/op
ClientPb.getUser:getUser·p0.999         sample          22.315           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.918           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.457           ms/op
ClientPb.listUser                       sample  229797   4.174 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.464           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.985           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.563           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.014           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.307           ms/op
ClientPb.listUser:listUser·p0.999       sample          18.560           ms/op
ClientPb.listUser:listUser·p0.9999      sample          33.561           ms/op
ClientPb.listUser:listUser·p1.00        sample          34.996           ms/op
